<template>
	<q-layout view="hHh lpR fFf">
		<q-header reveal elevated class="bg-primary text-white" height-hint="98">
			<q-toolbar>
				<q-toolbar-title class="text-bold">
					<span class="main-gradient">$BRDX</span>
				</q-toolbar-title>
			</q-toolbar>

			<q-tabs align="left">
				<q-route-tab to="/" label="Home" />
				<q-route-tab to="/swap" label="Swap" />
			</q-tabs>
		</q-header>

		<q-page-container class="bg-primary">
			<router-view />
		</q-page-container>
	</q-layout>
</template>

<script setup lang="ts">
defineOptions({
	name: 'MainLayout',
});
</script>

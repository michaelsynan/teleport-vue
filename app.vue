<template>
  <NuxtExampleLayout example="app/teleport">
    <div>
      <!-- Client Teleport -->
      <ClientOnly>
        <Teleport to="body">
          <div>Hello from a client-side teleport!</div>
        </Teleport>
      </ClientOnly>

      <!-- Modal Example -->
      <theModal />
    </div>
  </NuxtExampleLayout>
</template>

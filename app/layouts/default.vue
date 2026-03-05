<template>
  <div class="flex h-screen bg-[#0f1115] text-slate-200 overflow-hidden">
    <aside class="w-72 border-r border-slate-800 shrink-0">
      <LayoutSidebar />
    </aside>

    <main class="flex-1 flex flex-col relative overflow-hidden">
      <div class="flex-1 overflow-y-auto">
        <slot />
      </div>
      <LayoutPlayerBar />
    </main>
  </div>
</template>
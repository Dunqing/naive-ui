<markdown>
# Border

List can be bordered or unbordered.
</markdown>

<template>
  <n-list>
    <template #header>
      hhh
    </template>
    <template #footer>
      fff
    </template>
    <n-list-item>
      <template #prefix>
        <n-button>Prefix</n-button>
      </template>
      <template #suffix>
        <n-button>Suffix</n-button>
      </template>
      <n-thing title="Thing" title-extra="extra" description="description">
        Biu<br>
        Biu<br>
        Biu<br>
      </n-thing>
    </n-list-item>
    <n-list-item>
      <n-thing title="Thing" title-extra="extra" description="description">
        Biu<br>
        Biu<br>
        Biu<br>
      </n-thing>
      <template #suffix>
        <n-button>Suffix</n-button>
      </template>
    </n-list-item>
  </n-list>
</template>

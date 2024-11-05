<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Caring</template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Nature</template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Help</template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Tools</template>
  </WelcomeItem>
</template>
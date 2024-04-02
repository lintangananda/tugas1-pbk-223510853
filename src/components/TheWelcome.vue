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
      <DocumentationIcon />
    </template>
    <template #heading>Education</template>

    Computer Science of Harvard University
    <a href="https://vuejs.org/" target="_blank" rel="noopener">(2018-2022)</a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Experience</template>

    Full Time Programmer of
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Tokopedia (2022-2023)</a>. <br />IT Security of
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">Bank Jago (2023-2024)</a> 

    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ability</template>

    Teamwork,
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Editing</a>,
  Fast Learner,
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Hard Worker</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Skills</template>

    Java
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Photoshop</a>, Python,
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >C++</a
    >, GoLang
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>

    Instagram : 
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">@lintangganandaa</a>.
  </WelcomeItem>
</template>

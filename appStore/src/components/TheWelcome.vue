<script setup lang="ts">
import WelcomeItem from "./WelcomeItem.vue";
import PermitIcon from "./icons/IconPermit.vue";
import SystemConfigIcon from "./icons/IconSystemConfig.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <PermitIcon />
    </template>
    <template #heading>权限系统 </template>

    <a href="http://127.0.0.1:5173/" target="_blank" rel="noopener">Permit</a>
    是包含资源号，权限号的权限管理平台，方便进行用户角色配置。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SystemConfigIcon />
    </template>
    <template #heading>配置系统</template>

    
    <a
      href="http://127.0.0.1:5173/"
      target="_blank"
      rel="noopener"
      >SystemConfig</a
    >
    你可以在配置系统中实现自定义系统的流程设计及字段配置，创造自己需要的界面并进行步骤执行。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>动态流系统</template>

    
    <a href="http://127.0.0.1:5173/" target="_blank" rel="noopener">customization</a>
    根据配置系统中配置项生成对应界面，执行动态流。<br />

    1、待办中心<br />
    2、我的日记<br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading> 知识库</template>

    
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">knowledge System </a
    >重要数据整合平台，收集动态流中关键信息，并进行归纳整理及回顾<br />
    1、自动同步自定义系统中涉及知识；<br />
    2、存储空间大，内容不泄密；<br />
    3、文档能够分类管理；<br />
    4、多级栏目，界面展示简洁清晰，分享便捷；<br />
    5、团队协同功能，成员权限管理，能够在线编辑保存；<br />
    6、内容查找方便，能够快速精准的查找所需内容；<br />
    7、编辑功能简单好用易上手。<br />
    8、知识整合后回馈，可发平台共享。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>共享中心</template>

    优秀模板共享推荐，优秀知识同化分享。
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"
      >becoming a sponsor</a
    >.
  </WelcomeItem>
</template>

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
    <template #heading>Desarrollador FullStack en <a href="https://www.oneup-i.com/" target="_blank" rel="noopener"> <span class="text-green-500">OneUp</span></a></template>
    <span class="opacity-85">Nov 2022 - May 2023</span> <br>
    Desarrollo y soporte de requerimientos Landing Page, FTR y Addon Invoice. Soporte de sistema WebScraping y despliegue a producción (cloud).
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Practicante Pre Profesional en <a href="https://www.oneup-i.com/" target="_blank" rel="noopener"> <span class="text-green-500">OneUp</span></a></template>
    <span class="opacity-85">Nov 2022 - May 2023</span> <br>
    Soporte, gestión de Tickets, desarrollo e implementación de un módulo BI para el área de marketing de la empresa <a href="https://www.atsaairlines.com/" target="_blank" rel="noopener"> <span class="text-green-500">AtsaAirlines</span></a>
    <br />

    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>LAGONDA</template>
    <span class="opacity-85">Mar 2023 - Jul 2023</span> <br>
    Desarrollo de un Ecommerce aplicado a una empresa automotriz haciendo uso de servicios de Amazon Web
    services aplicando el modelo PaaS.<br>
    <template #logro >Top 2 en concurso de InfoFest | <a href="https://www.urp.edu.pe/" target="_blank" rel="noopener">Universidad Ricardo Palma</a> </template>

    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>SISGRAPH</template>
    <span class="opacity-85">Sept 2022 - Dic 2022</span> <br>
      Parte del equipo de desarrollo para la gestión operativa, cotizaciones y ventas de la empresa SISGRAPH
      implementando una arquitectura API Rest.<br>

    <span class="mt-2 text-sm text-rose-500">Top 1 en concurso de InfoFest | <a href="https://www.urp.edu.pe/" target="_blank" rel="noopener">Universidad Ricardo Palma</a> </span>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>TOQUE X</template>

    Parte del equipo de desarrollo para la gestión de inventario, almacenes y ventas.
    
  </WelcomeItem>
</template>

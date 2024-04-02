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
    <template #heading>PENDIDIKAN</template>
    TK BUNGA PERSADA<br>
    SDN 10 TUALANG<br>
    SMPN 2 TUALANG<br>
    SMKS YPPI TUALANG<br>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>HOBI</template>
  BERMAIN GAME<br>
  TRAVELING<br>
  OLAHRAGA<br>
    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>BIODATA</template>
TANGGAL LAHIR : 03-03-2004<br>
ASAL : PERAWANG<br>
NAMA AYAH : SYAIFUL EFFENDI<br>
NAMA IBU : DELIARNI NAINGGOLAN<br>
 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>PENGALAMAN HIDUP</template>
MAGANG DI PT BESRA<br>
HELPER SAFETY(PT TRUBA JAGA CITA)<br>
MAGANG DI GARUDA CYBER<br>
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>CONTACT ME</template>
WA : 081234567890<br>
IG : marlabuja<br>
FB : kevinalfariza<br>
TERIMAKASIH > ><br>

  </WelcomeItem>
</template>

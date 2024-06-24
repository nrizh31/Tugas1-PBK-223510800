<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Biodata</template>

    My Name is Naufal Rizh Aubi<br>
    you can call me Naufal <br>
    I from Pekanbaru, Riau <br>
    I was born in Yogyakarta, 31th of january <br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Educational Background</template>
    <ul>
      <li>TK PKK Sleman Yogyakarta 2008-2009</li>
      <li>SDN 143 Pekanbaru 2009-2015</li>
      <li>MTsN 1 Pekanbaru 2015-2018</li>
      <li>MAN 2 Pekanbaru 2018-2021</li>
      <li>Universitas Islam Riau 2022-now (Semester 4)</li>
      <li>Universitas Al-Azhar Indonesia 2023 (<i>Program Pertukaran Mahasiswa Merdeka</i>)</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
      <li>Graphic Design</li>
      <li>Database</li> 
      <li>Web Development</li> 
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Social Media</template>
    <p class="txt-mercury">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" width="2em" height="2em" fill="currentColor">
    <path d="M502.3 190.8L290.7 315c-7.9 4.4-17.6 4.4-25.5 0L9.7 190.8C1.5 186.3-2.4 176.6.8 167.3l26.1-89.5c3.2-11 12.9-17.6 23.1-17.6h408.2c10.1 0 19.9 6.5 23.1 17.6l26.1 89.5c3.1 9.2-.7 18.9-8.9 23.5zM256 352c-11.1 0-20-9-20-20v-75.9L20.5 168.1 16 480h480l-4.5-311.9L276 255.1V328c0 11-8.9 20-20 20z"/>
</svg>




E-Mail
      <a href="https://mail.google.com/mail/u/0/?view=cm&tf=1&fs=1&to=nrizh31@gmail.com">nrizh31@gmail.com</a>
    </p>
    <p class="txt-mercury">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" width="2em" height="2em" fill="currentColor">
        <path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9s-58-34.5-93.9-36.2c-37.5-1.8-149.9-1.8-187.4 0-35.9 1.7-67.7 9.9-93.9 36.2s-34.5 58-36.2 93.9c-1.8 37.5-1.8 149.9 0 187.4 1.7 35.9 9.9 67.7 36.2 93.9s58 34.5 93.9 36.2c37.5 1.8 149.9 1.8 187.4 0 35.9-1.7 67.7-9.9 93.9-36.2s34.5-58 36.2-93.9c1.8-37.5 1.8-149.9 0-187.4zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.8-99.5 9-132.1 9s-102.7 2.8-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.8-29.5-9-99.5-9-132.1s-2.8-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.8 99.5-9 132.1-9s102.7-2.8 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.8 29.5 9 99.5 9 132.1s2.8 102.7-9 132.1z"/>
      </svg> Instagram
      <a href="https://www.instagram.com/nrizh31/">@nrizh31</a>
    </p>
    
  </WelcomeItem>
</template>

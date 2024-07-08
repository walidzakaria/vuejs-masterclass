<script setupt lang='ts'></script>

<template>
  <div>
    <h1>Home Page</h1>
    <RouterLink to="/projects">Go to projects</RouterLink>
    <RouterLink :to="{ name: '/projects/[id]', params: { id: 'my project'} }">Specific Project</RouterLink>
  </div>
</template>
<template>
    <nav>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
      <NuxtLink :to="{ name: 'users-List' }">User List</NuxtLink>
    </nav>
  </template>
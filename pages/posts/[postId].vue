<template>
  <div>
    <div>postid: {{ $route.params.postid }}</div>
    <div>postId: {{ $route.params.postId }}</div>
    <div>post-id: {{ $route.params['post-id'] }}</div>
    <div>{{ $route.params }}</div>
  </div>
</template>

<script setup lang="ts"></script>

<template>
  <div>
    <h1>Lesson</h1>
    <p>This is a lesson</p>
    <p>This is a chapter name: {{ $route.params.chapterSlug }}</p>
    <p>This is a lesson name: {{ $route.params.lessonSlug }}</p>
  </div>
</template>
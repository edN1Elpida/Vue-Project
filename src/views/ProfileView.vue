<template>
  <div class="profile">
    <h1>This is an about page</h1>
    <hr>

  </div>
</template>

<style>

hr{
  width: 10rem;
}

.profile h1{
  font-size: 1rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}

@media (min-width: 1024px) {
  .profile {
    display: flex;
    flex-direction: column;
  }
}
</style>

<template>
  <div class="px-1 py-2 mx-auto border-2 border-solid rounded-lg shadow cardProfile">
    <div class="cardProfile__info">
      <img class="cardProfile__thumbnail" src="/imgs/profile-thumbnail.png" alt="Sarah Dole avatar">
      <ul class="cardProfile__textPair">
        <li class="text-lg font-semibold text-neutral-900"><i class="sr-only">Profile Name: </i>Sarah Dole</li>
        <li class="text-sm text-neutral-600"><i class="sr-only">Sarah Dole's ig account: </i>@sarahdole</li>
      </ul>
    </div>
    <p class="text-base text-neutral-600">I've been searching for high-quality abstract images for my design projects, and I'm thrilled to have found this platform. The variety and depth of creativity are astounding!</p>
  </div>
</template>

<style lang="scss">
.cardProfile {
  max-width: 340px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 24px;
  gap: 16px;
  background: #FFFFFF;
  border: 1px solid #E6E6E6;

  &__info {
    display: flex;
    gap: 16px;
  }
  
  &__thumbnail {
    width: 48px;
    height: 48px;
  }

  &__textPair {
    display: flex;
    flex-direction: column;
    gap: 1px;
  }
}
</style>

<template>
  <div class="news-page">
    <Head>
      <Title>Indel Cosmetics News</Title>
      <Meta name="og:title" content="Indel Cosmetics News" />
    </Head>
    <div class="container">
      <AppPageBanner title="Новини" />
      <div class="posts-list-container">
        <PostList :posts="posts" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    const posts = [
      {
        title: "Innovative Ingredient Improves Skin Hydration",
        category: "beauty",
        createdAt: "25 АПР 2023",
        image: "/images/product.jpeg",
      },
      {
        title:
          "Personal Care Company Partners with Sustainability Initiative to Promote Eco-Friendly Practices",
        category: "beauty",
        createdAt: "25 АПР 2023",
        image: "/images/product.jpeg",
      },
      {
        title: "Innovative Ingredient Improves Skin Hydration",
        category: "beauty",
        createdAt: "25 АПР 2023",
        image: "/images/product.jpeg",
      },
      {
        title: "Innovative Ingredient Improves Skin Hydration",
        category: "beauty",
        createdAt: "25 АПР 2023",
        image: "/images/product.jpeg",
      },
      {
        title: "Innovative Ingredient Improves Skin Hydration",
        category: "beauty",
        createdAt: "25 АПР 2023",
        image: "/images/product.jpeg",
      },
      {
        title:
          "Personal Care Company Partners with Sustainability Initiative to Promote Eco-Friendly Practices",
        category: "beauty",
        createdAt: "25 АПР 2023",
        image: "/images/product.jpeg",
      },
    ];

    return {
      posts,
    };
  },
};
</script>

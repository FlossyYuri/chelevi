<template>
  <section class="page_breadcrumbs ls background_cover section_padding_50">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 text-center">
          <h1 class="sr-only">{{ uri }}</h1>
          <ol class="breadcrumb darklinks">
            <li>
              <a href="./">{{ title }}</a>
            </li>
            <li class="active">
              <span>{{ uri }}</span>
            </li>
          </ol>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'BreadcrumbItem',
  props: {
    title: {
      type: String,
      default: 'Home',
    },
    uri: {
      type: String,
      default: '',
    },
  },
}
</script>

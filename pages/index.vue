<template>
  <div class="divide-y divide-gray-100">

    <Nav>
      <NavItem href="#" isActive>New Releases</NavItem>
      <NavItem href="#">Top Rated</NavItem>
      <NavItem href="#">Vincent’s Picks</NavItem>
    </Nav>
    <List>
      <ListItem />
    </List>

  </div>
</template>

<script lang="ts">
  import Nav from '../components/Nav.vue'
  import NavItem from '../components/NavItem.vue'
  import List from '../components/List.vue'
  import ListItem from '../components/ListItem.vue'

  export default {
    props: ['movies'],
    components: {
      Nav,
      NavItem,
      List,
      ListItem,
    },
  }
</script>

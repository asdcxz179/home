<template>
    <div>
        <header>
            <b-navbar toggleable="lg" type="dark" variant="info">
                <b-container fluid="lg">
        
                
                <b-navbar-brand href="#">歐酷雲設計工作室</b-navbar-brand>
        
                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        
                <b-collapse id="nav-collapse" is-nav>
                    <b-navbar-nav>
                    <b-nav-item href="#">關於我們</b-nav-item>
                    </b-navbar-nav>
        
                    <!-- Right aligned nav items -->
                    <b-navbar-nav class="ml-auto">
        
                    <!-- <b-nav-item-dropdown text="Lang" right>
                        <b-dropdown-item href="#">EN</b-dropdown-item>
                        <b-dropdown-item href="#">ES</b-dropdown-item>
                        <b-dropdown-item href="#">RU</b-dropdown-item>
                        <b-dropdown-item href="#">FA</b-dropdown-item>
                    </b-nav-item-dropdown> -->
        
                    <!-- <b-nav-item-dropdown right>
                        <template #button-content>
                        <em>User</em>
                        </template>
                        <b-dropdown-item href="#">Profile</b-dropdown-item>
                        <b-dropdown-item href="#">Sign Out</b-dropdown-item>
                    </b-nav-item-dropdown> -->
                    </b-navbar-nav>
                </b-collapse>
                </b-container>
            </b-navbar>
        </header>
        <main>
            <Nuxt/>
        </main>
        <footer>

        </footer>
    </div>
  </template>
  <script>
  export default {
    name: 'Main'
  }
  </script>
  
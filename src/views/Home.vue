<template>
  <div class="home"> </div>
    <navbar />
    <div id="main-section">
            <sidebar />
            <movie-list />
    </div>
</template>

<script>

  import Navbar from '../components/Navbar';
  import Sidebar from '../components/Sidebar';
  import MovieList from '../components/MovieList';
export default {
  name: 'Home',
  components: {
    Navbar,
    Sidebar,
    MovieList,
  }
}
</script>
<style lang="scss" scoped>
	.home {
		display: flex;
		flex-direction: column;

		#main-section {
			display: flex;
			margin-top: 50px;
		}
	}
</style>
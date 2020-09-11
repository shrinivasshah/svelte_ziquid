<script>
</script>

<header>
  <nav>
    <div><img src="./Logo.png" alt="logo" /></div>
    <div class="get_started"><button>Get Started</button></div>
  </nav>
</header>

<style>
    header {
	width: 100%;
	top: 0;
	left: 0;
	position: sticky;
	background-color: #f9fafb;
	box-shadow: 0px 20px 30px -10px rgba(104, 142, 176, 0.15);
	z-index: 10;
  }
  
  nav {
	width: 80%;
	margin: 0 auto;
	display: flex;
	align-items: center;
	justify-content: space-between;
	flex-grow: inherit;
	line-height: 100px;
  }
  
  nav .get_started button {
	line-height: 50px;
	width: 150px;
	background-color: #141414;
	color: #f9fafb;
	border-radius: 10px;
	border: none;
	transition: 1.3s;
	box-shadow: 0px 20px 30px -10px rgba(104, 142, 176, 0.15);
  }
  
  nav .get_started button:hover {
	box-shadow: 0px 20px 30px -10px rgba(104, 142, 176, 0.15);
	background: linear-gradient(146.82deg, #65a9e6 4.18%, #5c9ae0 90.5%);
  }
  
  nav img {
	width: 150px;
  }
</style>
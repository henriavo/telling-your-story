<style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }

      .b-example-divider {
        height: 3rem;
        background-color: rgba(0, 0, 0, .1);
        border: solid rgba(0, 0, 0, .15);
        border-width: 1px 0;
        box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
      }

      .b-example-vr {
        flex-shrink: 0;
        width: 1.5rem;
        height: 100vh;
      }

      .bi {
        vertical-align: -.125em;
        fill: currentColor;
      }

      .nav-scroller {
        position: relative;
        z-index: 2;
        height: 2.75rem;
        overflow-y: hidden;
      }

      .nav-scroller .nav {
        display: flex;
        flex-wrap: nowrap;
        padding-bottom: 1rem;
        margin-top: -1px;
        overflow-x: auto;
        text-align: center;
        white-space: nowrap;
        -webkit-overflow-scrolling: touch;
      }

      .icon-list li::before {
		  display: block;
		  flex-shrink: 0;
		  width: 1.5em;
		  height: 1.5em;
		  margin-right: .5rem;
		  content: "";
		  background: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23212529' viewBox='0 0 16 16'%3E%3Cpath d='M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z'/%3E%3C/svg%3E") no-repeat center center / 100% auto;
	}

    </style>

     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>


<div class="col-lg-8 mx-auto p-4 py-md-5">
  <header class="d-flex align-items-center pb-3 mb-5 border-bottom">
    <a href="/" class="d-flex align-items-center text-dark text-decoration-none">
     <svg width="32" height="32" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <path id="Color-Fill" fill="#79a1a1" stroke="none" d="M 0 0 L 32 0 L 32 32 L 0 32 Z"/>
    <g id="Logo-Placeholder-Replace-With-Your-Logo-">
        <text id="text1" xml:space="preserve" x="6.680014" y="21" font-family="Bebas Neue" font-size="16.853097" font-weight="700" fill="#0d0d0b" letter-spacing="-0.337062">HI</text>
    </g>
	</svg>
      <span class="fs-4">Welcome</span>
    </a>
  </header>

  <main>
    <h1>Hey my name is Henri</h1>
    <p class="fs-5 col-md-8">I'm a sofware developer living in Chicago. I've been profesionally coding for about 10 years. But I'm new to the web stack, and this is an example of something I depoyed. </p>

    <div class="mb-5">
      <a href="https://henri-public-bucket.s3.us-east-2.amazonaws.com/merry_christmas_2022.jpg" class="btn btn-primary btn-lg px-4" target="_blank">Click here for an xmas card</a>
    </div>

    <hr class="col-3 col-md-2 mb-5">

    <div class="row g-5">
      <div class="col-md-6">
        <h2>Projects</h2>
        <p>I've settled on a language, framework, and cloud provider. So my goal is start building and deploying. All code is on my public github. </p>
        <ul class="icon-list ps-0">
          <li class="d-flex align-items-start mb-1"><a href="https://github.com/henriavo/telling-your-story" rel="noopener" target="_blank">Sourc code for this website</a></li>
          <li class="text-muted d-flex align-items-start mb-1">(more coming soon!)</li>
        </ul>
      </div>

      <div class="col-md-6">
        <h2>Tools</h2>
        <p>Read more detail about the libraries and frameworks I'm currently working with.</p>
        <ul class="icon-list ps-0">
          <li class="d-flex align-items-start mb-1"><a href="https://kit.svelte.dev/" target="_blank">SvelteKit for the backend</a></li>
          <li class="d-flex align-items-start mb-1"><a href="https://getbootstrap.com/" target="_blank">Bootstrap for the frontend</a></li>
          <li class="d-flex align-items-start mb-1"><a href="https://www.digitalocean.com/" target="_blank">Digital Ocean for deployment</a></li>
         
        </ul>
      </div>
    </div>
  </main>
  <footer class="pt-5 my-5 text-muted border-top">
    Created by the Bootstrap team &middot; &copy; 2022
  </footer>
</div>


   



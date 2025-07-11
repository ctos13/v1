<script>
  import { page } from "$app/state";
  let route = $derived(page.route.id.replaceAll("/", ""));
</script>

<main>
  <nav class="navbar-start container">
    <ul>
      <!-- <li><a href="mailto:">Share your story</a></li> -->
      <li>
        <details class="dropdown bg-base-200">
          <summary>{route ? route : "Home"}</summary>
          <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/abuse">Abuse</a></li>
            <li><a href="/predator">Sexual Predator</a></li>
            <li><a href="/fraud">Fraud & Coercion</a></li>
          </ul>
        </details>
      </li>
    </ul>
    <ul>
      <li>
        <a href="/">
          <strong>The Real Phil LeVota</strong>
        </a>
      </li>
    </ul>
  </nav>
</main>

<style>
  strong {
    font-size: 1.5rem;
  }
</style>

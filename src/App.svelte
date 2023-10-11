<script>
  let auth = {
    loggedIn: false
  }

  const handleLogin = () => auth.loggedIn = true;
  const handleLogout = () => auth.loggedOut = false;
</script>

<button on:click={handleLogin}>Log In</button>
<button on:click={handleLogout}>Log Out</button>

{#if auth.loggedIn === true} 
<p>로그인 중입니다.</p>
{:else}
<p>로그아웃 중입니다.</p>
{/if}
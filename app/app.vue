<template>
  <div class="container">
    <div class="content">
      <svg
        class="logo"
        viewBox="0 0 221 65"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g clip-path="url(#a)">
          <path fill="#00DC82" d="M82.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M118.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M154.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M190.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M82.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M118.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M154.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M190.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M82.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M118.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M154.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M190.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M82.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M118.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M154.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M190.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M82.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M118.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M154.5 62.5h36V0h-36z" />
          <path fill="#00DC82" d="M190.5 62.5h36V0h-36z" />
        </g>
        <defs>
          <clipPath id="a"><path fill="#fff" d="M0 0h221v65H0z" /></clipPath>
        </defs>
      </svg>
      <h1>Welcome to Nuxt, this website was created using service from a git push!</h1>
      <p>You've successfully created a Nuxt project. Well done!</p>
      <div class="links">
        <a href="https://nuxt.com/docs" target="_blank">Documentation</a>
        <a href="https://nuxt.com/modules" target="_blank">Modules</a>
        <a href="https://nuxt.com/examples" target="_blank">Examples</a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #00dc82 0%, #36e4da 50%, #0047e1 100%);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
}

.content {
  text-align: center;
  padding: 2rem;
  background: rgba(255, 255, 255, 0.95);
  border-radius: 16px;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
  max-width: 600px;
}

.logo {
  width: 180px;
  height: auto;
  margin-bottom: 2rem;
}

h1 {
  font-size: 2.5rem;
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 1rem;
}

p {
  font-size: 1.1rem;
  color: #5a6c7d;
  margin-bottom: 2rem;
  line-height: 1.6;
}

.links {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.links a {
  padding: 0.75rem 1.5rem;
  background: #00dc82;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-weight: 600;
  transition: all 0.3s ease;
}

.links a:hover {
  background: #00b86b;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 220, 130, 0.4);
}
</style>

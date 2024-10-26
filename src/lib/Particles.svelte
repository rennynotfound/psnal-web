<script>
    import { loadFull } from "tsparticles";
    import { tsParticles } from "tsparticles-engine";
  
    const particlesInit = async (main) => {
      await loadFull(tsParticles);
    };
  
    const particlesOptions = {
      // Paste the CodePen JavaScript options here, converting it to JSON if necessary.
    };
  </script>
  
  <div class="absolute inset-0 -z-10">
    <Particles id="tsparticles" options={particlesOptions} init={particlesInit} />
  </div>

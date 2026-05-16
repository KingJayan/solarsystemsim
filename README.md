<div align="center">
  <h2><code>KingJayan/solarsystemsim</code></h2>
  <p>simple solar system sim with three.js</p>
</div>

>[!IMPORTANT]
>in alpha but wont really be updated
- **limitations:**

  1. **Scale**  
     space is big, so we use a *visual scale* (see the `CONFIG` object) for visuality, while staying kinda proportional

  2. **orbits**  
     keplerian elements:  
     - **ecc** (eccentricity): how stretched the orbit is (0 = circle, 1 = parabola)  
     - **inc** (inclination): tilts the orbital plane relative to the Sun’s equator
     - **tilt** (obliquity): tilts the planet itself (hello seasons)

  3. **textures**  
     no external textures(i might add textures later-i suck at 3d modeling)

  4. **perf**  
     if your GPU starts crashing out, lower the asteroid count  
     (default is 4000 instances) or reduce shadow map resolution.
     `InstancedMesh` keeps the asteroid belt from melting your calls

  5. **html-ness**
     whole project was made in one standalone HTML file using three.js.
     some features are trickier to implement than in a full build setup,  
     but the tradeoff is zero dependencies and instant portability.

(first threejs project, so dont expect it to work flawlessly)

<div align="center"><p>made with :) by jayan</p></div>

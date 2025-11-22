- **Welcome to the Solar System Sim**
_in alpha but wont really be updated_
- **desc and limitations:**

  1. **Scale**  
     Space is stupid huge. If we used true scale, every planet would be a pixel crying in a sea of black.  
     So we use a *visual scale* (see the `CONFIG` object) for visuality, while staying kinda proportional.

  2. **Orbits**  
     Keplerian elements:  
     - **ecc** (eccentricity): how stretched the orbit is (0 = circle, 1 = parabola).  
     - **inc** (inclination): tilts the orbital plane relative to the Sun’s equator.  
     - **tilt** (obliquity): tilts the planet itself (hello seasons).

  3. **Textures**  
     No external textures

  4. **Performance**  
     If your GPU starts crashing out, lower the asteroid count  
     (default is 4000 instances) or reduce shadow map resolution.  
     `InstancedMesh` keeps the asteroid belt from melting your calls.

  5. **HTML-ness**
     This whole project was made in one standalone HTML file using three.js.  
     That means some features are trickier to implement than in a full build setup,  
     but the tradeoff is zero dependencies, instant portability, and permanent brain damage(jk).

*– Jayan P*

(this is my first threejs project, so dont expect it to work)

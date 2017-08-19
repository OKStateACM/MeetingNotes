* CS research is *confusing!*
  * Confusing CS research is an opportunity to learn more
    * These papers have passed the test of a reputable conference

* Research in CS generally means creating an algorithm to to solve a problem, as well as describing the attributes of that algorithm.
  * Inventing new fields
  * Optimization

* Paper structure
  * _Abstract_ -- single-paragraph summary
  * Introduce field and the specific problem
  * Directly state contributions of paper, what's novel
  * Related work providing context of paper
  * Mathematical framework of algorithm
  * How algorithm solves the problem, methodology -- ideally detailed enough to re-implement the technique
  * Hardware the algorithm was tested on, tests done, comparison to previous tests
  * Conclusion, possible future work
    
* Klehm et al.'s paper "Prefiltered Single Scattering"
  * Crepuscular/god rays -- The rays of light that appear in the sky
  * L*i*(x, w*i*) = T*r*(x, x*s*) * L*s*(x*s*, -w*i*) + ∫[0,s] T*r*(x, x*t*) * σ*t*(x*t*) * L*scat*(x*t*, -w*i*) dt
  
* Reading papers
  * Understand the math
      * L terms are *radiance* -- light flow
      * T*r* terms are transmittances -- what percentages of light get from one end to the next?
      * Integral means we're summing up a quantity that can vary
      * L*scat* is scattered light -- the more confusing bit that Klehm et al. are really trying to get at
        * Draw a diagram if need be
          * T*r*(x, x*s*) * L*s*(x*s*, -w*i*) is the light reflected from the first solid surface that the light hits
          * T*r*(x, x*t*) * σ*t*(x*t*) is the light reflected from the medium (like fog) that the light hits (where σ*t* is the thickness of the fog
          * Klehm et al. show how L*scat* is currently being calculated. Then they one-up that current understanding with their own algorithm.
           * Previous work optimized by ray marching, assuming a uniform medium, shadow-mapping, using min/max trees to block out larger regions as shadowed

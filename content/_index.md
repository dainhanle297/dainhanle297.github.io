---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: "📚 My Research"
      subtitle: ""
      text: |-
        <div align="justify">
        Use this area to introduce your mission. I'm a researcher in structural engineering with a focus on artificial intelligence and computational modelling. My work explores advanced deep learning and hybrid machine learning methods for predicting the behavior of steel and concrete structures.
  
        I aim to bridge structural engineering and AI to develop resilient and sustainable infrastructure.
  
        Feel free to reach out for collaboration 🤝
        </div>
    
    
 - block: markdown
  content:
    title: "📚 Recent Publications"
    subtitle: ""
    text: |-
      **Journal Articles**

      - **D.-N. Le**, Q.-V. Vu, T.-H. Pham, V.-T. Huynh, and S. Tangaramvong.  
        "CurveSPG: An efficient framework for generating structural curves of the unstiffened steel plate girder under patch loading based on modified denoise diffusion model."  
        *Thin-Walled Structures*, vol. 216, p. 113739, 2025.  
        [doi:10.1016/j.tws.2025.113739](https://doi.org/10.1016/j.tws.2025.113739)

      - **D.-N. Le**, T.-H. Pham, T.-D. Pham, Z. Kong, G. Papazafeiropoulos, and Q.-V. Vu.  
        "An efficient long short-term memory-based model for prediction of the load-displacement curve of concrete-filled double-skin steel tubular columns."  
        *Construction and Building Materials*, vol. 449, p. 138122, 2024.  
        [doi:10.1016/j.conbuildmat.2024.138122](https://doi.org/10.1016/j.conbuildmat.2024.138122)

      - **D.-N. Le**, T.-H. Pham, G. Papazafeiropoulos, Z. Kong, V.-L. Tran, and Q.-V. Vu.  
        "Hybrid machine learning with Bayesian optimization methods for prediction of patch load resistance of unstiffened plate girders."  
        *Probabilistic Engineering Mechanics*, vol. 76, p. 103624, 2024.  
        [doi:10.1016/j.probengmech.2024.103624](https://doi.org/10.1016/j.probengmech.2024.103624)

      - Q.-V. Vu, **D.-N. Le**, T.-D. Pham, W. Gao, and S. Tangaramvong.  
        "An efficient procedure for prediction of the load-displacement curve of CFDST columns."  
        *Journal of Constructional Steel Research*, vol. 224, p. 109113, 2025.  
        [doi:10.1016/j.jcsr.2024.109113](https://doi.org/10.1016/j.jcsr.2024.109113)

      - Z. Kong, **D.-N. Le**, T.-H. Pham, K. Poologanathan, G. Papazafeiropoulos, and Q.-V. Vu.  
        "Hybrid machine learning with optimization algorithm and resampling methods for patch load resistance prediction of unstiffened and stiffened plate girders."  
        *Expert Systems with Applications*, vol. 249, p. 123806, 2024.  
        [doi:10.1016/j.eswa.2024.123806](https://doi.org/10.1016/j.eswa.2024.123806)

      - D.-K. Thai, **D.-N. Le**, Q. H. Doan, T.-H. Pham, and D.-N. Nguyen.  
        "A hybrid model for classifying the impact damage modes of fiber reinforced concrete panels based on XGBoost and Horse Herd Optimization algorithm."  
        *Structures*, vol. 60, p. 105872, 2024.  
        [doi:10.1016/j.istruc.2024.105872](https://doi.org/10.1016/j.istruc.2024.105872)

      - D.-K. Thai, **D.-N. Le**, Q. Hoan Doan, T.-H. Pham, and D.-N. Nguyen.  
        "Classification models for impact damage of fiber reinforced concrete panels using Tree-based learning algorithms."  
        *Structures*, vol. 53, pp. 119–131, 2023.  
        [doi:10.1016/j.istruc.2023.04.062](https://doi.org/10.1016/j.istruc.2023.04.062)

      **Conference Proceedings**

      - **D.-N. Le**, Q.-V. Vu, and S. Tangaramvong.  
        "An efficient deep learning approach for predicting the ultimate load and maximum lateral web deformation of unstiffened steel plate girders under patch loading."  
        In *Proceeding of The 30th National Convention on Civil Engineering*, vol. 30, 2025.


  
---

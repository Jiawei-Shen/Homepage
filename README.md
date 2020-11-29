---
pageClass: home-page
# some data for the components

name: Jiawei Shen
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/Jiawei-Shen
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: https://www.instagram.com

cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: Student at Wuhan University
email: harry (at) hogwarts (dot) edu
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I attended [Hogwarts School of Witchcraft and Wizardry](https://en.wikipedia.org/wiki/Hogwarts) to study witchcraft, supervised by **Dumbledore** and other professors. 

I'm trying my best to battle with Lord Voldemort, the evil Wizard that we all fear. My research area includes Defence Against the Dark Arts and other magic. :dizzy:



## Education & Experiences

- **Wuhan University #China National University Ranking 12** <br/>
Sept. 2017 - Now

- **University of California, Berkerley (Summer School)** <br/>
June 2018 - Aug. 2018


## Projects


[→ Full list](/projects/)

<ProjectCard image="/projects/1.png" hideBorder=true>

  **Implicit Euler ODE Networks for Single-Image Dehazing Based on Implicit Structure**

  Jiawei Shen, *et al*
  
 Inspiring from the Euler method, we considered Residual Network (Res-Net) an explicit scheme network, which associates with implicit scheme, 
 then we introduce a network based on implicit scheme to process low-level tasks. 
 
 
  [[Paper](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w14/Shen_Implicit_Euler_ODE_Networks_for_Single-Image_Dehazing_CVPRW_2020_paper.pdf)] 
  [[Github](https://github.com/Jiawei-Shen/MI-Net)]
  
</ProjectCard>


<ProjectCard hideBorder=true>

  **Technical Research of Super-Resolution Image Reconstruction based on a lightweight network**
  Wenlan Wei, Juan Du, Jiawei Shen, Ziyu Zhou, *et al*
  
  Using Network Pruning, Weight Sharing, and Quantitative interception to reduce the weight of the network. 

  [[Paper](https://ieeexplore.ieee.org/abstract/document/9045996)] 
  [[Github](https://github.com/weiwenlan/Mobile-Lightweight-Super-Resolution-Construction-System)]

</ProjectCard>


<ProjectCard hideBorder=true>

  **A Lightweight Network to Learn Optical Flow from Event Data**
  Zhuoyan Li, Jiawei Shen, *et al*
  
  Intergrating Laplacian pyramidal processing into Convolutional Neural Network (CNN), we proposed an lightweight network to process the optical flow 
  information from event data in event camera. 

  [[Paper]()] 
  

</ProjectCard>


## Awards & Honors

### Contests

- "Meritorious Winner" prize in **Mathematical Contest In Modeling**


<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>

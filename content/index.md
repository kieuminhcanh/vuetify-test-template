---
title: "Professional Profile"
description: "A modern professional profile template"
---

::v-container{fluid class="pa-0"}
  ::v-row{no-gutters}
    ::v-col{cols="12" alias="Profile"}
      ::v-card{variant="flat" color="primary" class="text-white"}
        ::v-card-text{class="pa-8"}
          ::v-row{align="center"}
            ::v-col{cols="12" md="3" class="text-center"}
              ::v-avatar{size="150" color="white" text="JD"}
              ::
            ::

            ::v-col{cols="12" md="9"}
            # John Doe

              ::v-chip{text="Full Stack Developer" color="white" variant="outlined" class="ma-1"}
              ::
              ::v-chip{text="UI/UX Designer" color="white" variant="outlined" class="ma-1"}
              ::
              ::v-chip{text="Tech Enthusiast" color="white" variant="outlined" class="ma-1"}
              ::
            
            Passionate developer with 5+ years of experience in building modern web applications. Specialized in Vue.js, Nuxt.js, and Vuetify frameworks.
            ::
          ::
        ::
      ::
    ::
  ::

  ::v-row{class="mt-4"}
    ::v-col{cols="12" md="4"}
      ::v-card{title="Contact Information" variant="outlined"}
        ::v-list{density="compact"}
          ::v-list-item{title="Email" subtitle="john.doe@example.com" prepend-icon="mdi-email"}
          ::
          ::v-list-item{title="Phone" subtitle="+1 234 567 8900" prepend-icon="mdi-phone"}
          ::
          ::v-list-item{title="Location" subtitle="San Francisco, CA" prepend-icon="mdi-map-marker"}
          ::
          ::v-list-item{title="Website" subtitle="https://johndoe.dev" prepend-icon="mdi-web"}
          ::
        ::
      ::

      ::v-card{title="Skills" variant="outlined" class="mt-4"}
        ::v-card-text
          ::v-chip{text="Vue.js" color="primary" variant="flat" size="small" class="ma-1"}
          ::
          ::v-chip{text="Nuxt.js" color="primary" variant="flat" size="small" class="ma-1"}
          ::
          ::v-chip{text="TypeScript" color="primary" variant="flat" size="small" class="ma-1"}
          ::
          ::v-chip{text="Vuetify" color="primary" variant="flat" size="small" class="ma-1"}
          ::
          ::v-chip{text="Node.js" color="secondary" variant="flat" size="small" class="ma-1"}
          ::
          ::v-chip{text="MongoDB" color="secondary" variant="flat" size="small" class="ma-1"}
          ::
          ::v-chip{text="GraphQL" color="secondary" variant="flat" size="small" class="ma-1"}
          ::
          ::v-chip{text="Docker" color="secondary" variant="flat" size="small" class="ma-1"}
          ::
        ::
      ::

      ::v-card{title="Languages" variant="outlined" class="mt-4"}
        ::v-card-text
          ::v-row{align="center" class="mb-2"}
            ::v-col{cols="4"}
            **English**
            ::
            ::v-col{cols="8"}
              ::v-progress-linear{modelValue="100" color="success" height="8" rounded}
              ::
            ::
          ::

          ::v-row{align="center" class="mb-2"}
            ::v-col{cols="4"}
            **Spanish**
            ::
            ::v-col{cols="8"}
              ::v-progress-linear{modelValue="75" color="info" height="8" rounded}
              ::
            ::
          ::

          ::v-row{align="center" class="mb-2"}
            ::v-col{cols="4"}
            **French**
            ::
            ::v-col{cols="8"}
              ::v-progress-linear{modelValue="50" color="warning" height="8" rounded}
              ::
            ::
          ::
        ::
      ::
    ::

    ::v-col{cols="12" md="8"}
      ::v-card{title="About Me" variant="outlined"}
        ::v-card-text
        I am a passionate full-stack developer with extensive experience in creating modern,
        responsive web applications. My expertise lies in Vue.js ecosystem, particularly Nuxt.js
        and Vuetify, which allows me to build beautiful and performant user interfaces.

        Throughout my career, I've worked on various projects ranging from e-commerce platforms
        to enterprise SaaS applications. I believe in writing clean, maintainable code and
        following best practices in software development.

        When I'm not coding, you can find me contributing to open-source projects, writing
        technical blog posts, or exploring new technologies.
        ::
      ::

      ::v-card{title="Work Experience" variant="outlined" class="mt-4"}
        ::v-timeline{side="end" density="compact"}
          ::v-timeline-item{dot-color="primary" size="small"}
            ::v-card{title="Senior Frontend Developer" subtitle="Tech Corp · 2021 - Present" variant="tonal"}
              ::v-card-text
              - Led the development of a new product dashboard using Vue 3 and TypeScript
              - Improved application performance by 40% through code optimization
              - Mentored junior developers and conducted code reviews
              - Implemented CI/CD pipeline using GitHub Actions
              ::
            ::
          ::

          ::v-timeline-item{dot-color="secondary" size="small"}
            ::v-card{title="Frontend Developer" subtitle="Digital Agency · 2019 - 2021" variant="tonal"}
              ::v-card-text
              - Developed responsive web applications for various clients
              - Collaborated with designers to implement pixel-perfect UIs
              - Integrated REST APIs and GraphQL endpoints
              - Conducted user testing and implemented feedback
              ::
            ::
          ::

          ::v-timeline-item{dot-color="success" size="small"}
            ::v-card{title="Junior Developer" subtitle="StartUp Inc · 2018 - 2019" variant="tonal"}
              ::v-card-text
              - Assisted in developing company's main web application
              - Fixed bugs and implemented new features
              - Participated in agile development process
              - Learned best practices in software development
              ::
            ::
          ::
        ::
      ::

      ::v-card{title="Education" variant="outlined" class="mt-4"}
        ::v-list{density="comfortable"}
          ::v-list-item{title="Bachelor of Science in Computer Science" subtitle="University of Technology · 2014 - 2018"}
          GPA: 3.8/4.0
          ::

          ::v-divider{class="my-2"}
          ::

          ::v-list-item{title="Certifications"}
          - AWS Certified Developer - Associate (2022)
          - Vue.js Master Certification (2021)
          - Scrum Master Certification (2020)
          ::
        ::
      ::

      ::v-card{title="Projects" variant="outlined" class="mt-4"}
        ::v-row
          ::v-col{cols="12" sm="6"}
            ::v-card{title="E-Commerce Platform" text="A modern e-commerce solution built with Nuxt 3, Vuetify, and Stripe integration." variant="outlined" hover}
              ::v-img{src="https://placehold.co/300x200" aspect-ratio="1.5" cover}
              ::
              ::v-card-actions
                ::v-btn{text="GitHub" variant="text" color="primary" prepend-icon="mdi-github"}
                ::
                ::v-btn{text="Live Demo" variant="text" color="secondary" prepend-icon="mdi-open-in-new"}
                ::
              ::
            ::
          ::

          ::v-col{cols="12" sm="6"}
            ::v-card{title="Task Management App" text="A collaborative task management tool with real-time updates using Socket.io." variant="outlined" hover}
              ::v-img{src="https://placehold.co/300x200" aspect-ratio="1.5" cover}
              ::
              ::v-card-actions
                ::v-btn{text="GitHub" variant="text" color="primary" prepend-icon="mdi-github"}
                ::
                ::v-btn{text="Live Demo" variant="text" color="secondary" prepend-icon="mdi-open-in-new"}
                ::
              ::
            ::
          ::

          ::v-col{cols="12" sm="6"}
            ::v-card{title="Portfolio Website" text="A creative portfolio website showcasing design and development work." variant="outlined" hover}
              ::v-img{src="https://placehold.co/300x200" aspect-ratio="1.5" cover}
              ::
              ::v-card-actions
                ::v-btn{text="GitHub" variant="text" color="primary" prepend-icon="mdi-github"}
                ::
                ::v-btn{text="Live Demo" variant="text" color="secondary" prepend-icon="mdi-open-in-new"}
                ::
              ::
            ::
          ::

          ::v-col{cols="12" sm="6"}
            ::v-card{title="Weather Dashboard" text="A weather forecast application with interactive maps and detailed analytics." variant="outlined" hover}
              ::v-img{src="https://placehold.co/300x200" aspect-ratio="1.5" cover}
              ::
              ::v-card-actions
                ::v-btn{text="GitHub" variant="text" color="primary" prepend-icon="mdi-github"}
                ::
                ::v-btn{text="Live Demo" variant="text" color="secondary" prepend-icon="mdi-open-in-new"}
                ::
              ::
            ::
          ::
        ::
      ::

      ::v-card{title="Testimonials" variant="outlined" class="mt-4"}
        ::v-row
          ::v-col{cols="12" md="6"}
            ::v-card{variant="tonal" color="primary"}
              ::v-card-text
                ::v-icon{icon="mdi-format-quote-open" size="48" class="mb-2"}
                ::

              John is an exceptional developer who consistently delivers high-quality work.
              His attention to detail and problem-solving skills are outstanding.

                ::v-divider{class="my-3"}
                ::

              **Sarah Johnson**
              Product Manager at Tech Corp
              ::
            ::
          ::

          ::v-col{cols="12" md="6"}
            ::v-card{variant="tonal" color="secondary"}
              ::v-card-text
                ::v-icon{icon="mdi-format-quote-open" size="48" class="mb-2"}
                ::

              Working with John was a pleasure. He brought creative solutions to complex
              problems and always met deadlines.

                ::v-divider{class="my-3"}
                ::

              **Michael Chen**
              CTO at Digital Agency
              ::
            ::
          ::
        ::
      ::

      ::v-card{variant="flat" color="success" class="text-white mt-4"}
        ::v-card-text{class="text-center py-8"}
        ## Let's Work Together!

        I'm always interested in hearing about new projects and opportunities.

          ::v-btn{text="Get In Touch" variant="elevated" color="white" size="large" prepend-icon="mdi-email" class="mt-4"}
          ::
        ::
      ::
    ::
  ::
::

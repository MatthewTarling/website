---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-30
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: matthew-tarling
    design:
      background:
        image:
      # Name of image in `assets/media/`.
          filename: Aoraki.png
      # Apply image filters?
          filters:
        # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 1
      #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
      # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
      # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: false
      # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: false

  - block: portfolio
    id: projects
    content:
      title: Research 
      subtitle: 
      text: "My researched is centered on developing a better understanding of the structure, deformation behaviour and evolution of large faults and shear zones over the seismic cycle. 

    
      
      My work explores how the interaction of structure, rock deformation processes, and mineral reactions influences the slip behaviour of faults. Using observational field geology as the foundation of my methodology, I apply a field-to-nanoscale approach, starting at the scale of the mountainside outcrop, and working my way all the way down to the crystal lattice of the minerals within. This multi-scale approach allows me to probe questions across many spatial and temporal orders of magnitude, from the scale of the subduction megathrusts to the geological outcrop, down to a mineral’s crystal lattice, all the while pondering timescales ranging from an entire orogeny to the near-instantaneous earthquake rupture.



      Here is (an incomplete) list of few of my project that will grow as I update this site. 


      
      <br>
      <br>
      <br>
      
      "

      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: Here you will find a list of my peer-reviewed paper. If you would like a pdf copy of anything listed, don't hesitate to ask!
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  # - block: collection
  #   id: 3D-printing
  #   content:
  #     title: 3D Printing
  #     subtitle: I've recently been playing around with the intersection of 3D printing and the Earth Science. On this page you will find some of these little projects, with the .STL files for you to try printing them yourself! Don't hesitate to drop me a line if you need a hand with something or have any questions!
  #     filters:
  #       folders:
  #         - 3D-printing
  #   design:
  #     columns: '2'
  #     view: compact
    # - block: markdown
    #   id: outreach
    # content:
    #   title: Viewing the Rock World
    #   subtitle: check this out!
    #   filters:
    #     folders:
    #       - 3D-printing
    # design:
    #   columns: '2'
    #   view: compact
    # design:
    #   columns: '1'
  - block: markdown
    content:
      title: Photos from the field!
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: matthew.tarling@mcgill.ca
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        # street: 450 Serra Mall
        city: Montréal
        region: Québec
        # postcode: '94305'
        country: Canada
        country_code: CA
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/rocksbydefault'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---

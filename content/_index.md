---
# Leave the homepage title empty to use the site title
title: Amy Orben
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: markdown
    content:
      title: Research
      subtitle: ''
      text: Dr Orben's research examines how digital technologies affect adolescent psychological well-being and mental health. She is particularly interested in the potential cognitive, biological and social mechanisms that underlie this link in both non-clinical and clinical populations, and the influence of individual differences. To study such research questions, Amy’s team uses innovative and rigorous statistical methodology, secondary datasets, and Open Science approaches. Her results, in turn, shed new light on pressing questions debated in policy, parenting and mental health, having informed advice given by national and international experts such as the UK Chief Medical Officers and the US Surgeon General.
    design:
      columns: '2'
  - block: markdown
    content:
      title: Prizes and Recognition
      subtitle: ''
      text: Amy is a member of the UK Department for Digital, Culture, Media and Sport “College of Experts” giving direct advice to government, as well as the British Academy Public Policy Committee. She also sits on the University of Cambridge Open Research Steering Committee and the ESRC New and Emerging Forms of Data Leadership Group. She has won the Inaugural MRC Early Career Impact Award, the British Neuroscience Association Researcher Credibility Prize, the Society for the Improvement of Psychological Science Mission Award and the UK Reproducibility Network Dorothy Bishop Early Career Researcher Prize for her work to improve scientific practices. At both the University of Oxford and the University of Cambridge Amy has received nominations for student-led teaching awards.
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---

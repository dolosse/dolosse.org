---
layout: home
header:
  title: Scalable and Maintainable Physics Data Acquisition
  text: >
    From small single channel experiments to gargantuan thousand channel projects
    our system offers world-class support.
  action: # action button is optional
    label: Find Out More
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: We've got you covered!
    text: Dolosse combines data science industry standards with cutting-edge physics hardware to provide an extensible, scalable and redundant data framework.   
    actions:
      - title: Contact Us!
        url: '#contacts'
        class: btn-light

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: Our Three Divisions
    services:
      - title: Acquisition
        text: Kafka provides Dolosse’s core infrastructure. Using a multi-producer/consumer model, we distribute the workload to maximize throughput.
        icon: fa-network-wired
      - title: Analysis
        text: We combine Spark and Python to provide world-class tools for your data analysis. We store data in parquet format to maximize flexibility.
        icon: fa-database
      - title: Visualization
        text: Kibana allows users to monitor experimental health with alerts and dashboards. Plotly allows users to analyze data inside a webapp.
        icon: fa-chart-line

  - type: aside.html
    section_id: aside
    title: Open-source code available at Github!
    actions:
      - title: Browse the code!
        url: https://github.com/dolosse/dolosse
        class: btn-light

  - type: members.html
    section_id: members
    title: Dolosse Members
    background_style: bg-info text-white
    members:
      - title: S. V. Paulauskas
        text: Founder
        image: assets/img/members/professionalLooking.jpg
        url: 'http://stanpaulauskas.com'
      - title: iThemba LABS
        text: Software Lead
        image: assets/img/members/ithemba_profile.jpg
        url: 'https://tlabs.ac.za/'

  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to supercharge your experiments? Drop us a line on Github or chat with us on Slack!
    actions:
    - title: Github
      icon: fa-github
      icon_type: fab
      url: 'https://github.com/dolosse/dolosse/issues/new?assignees=spaulaus&labels=question&template=question.md'
    - title: Slack
      icon: fa-slack
      icon_type: fab
      url: 'https://join.slack.com/t/dolosse/signup'

---

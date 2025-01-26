
site_name: Ólöf - Fab Academy
site_url: https://fabacademy.org/2025/labs/isafjordur/students/olof-hannesdottir/
repo_url: https://gitlab.fabcloud.org/academany/fabacademy/2025/labs/isafjordur/students/olof-hannesdottir
repo_name: olof/fabacademy
site_dir: public

theme:
  name: material 

  features:
    - header.autohide
    - navigation.tabs
    - navigation.tabs.sticky
    - navigation.sections
    - navigation.instant
    - navigation.tracking
    - navigation.top
    - content.code.annotate
    - custom_dir: docs/overrides
    
    logo: docs/img01/LogoIcelandic_WhitemoreSpace.png
    favicon: LogoIcelandic_PinkmoreSpace.svg

  palette:
    - media: "(prefers-color-scheme: light)"
      scheme: default
      toggle:
        icon: material/toggle-switch-off-outline 
        name: Switch to dark mode
      primary: indigo
      accent: black 
    - media: "(prefers-color-scheme: dark)"
      scheme: slate 
      toggle:
        icon: material/toggle-switch
        name: Switch to light mode    
      primary: indigo
      accent: cyan
  font:
    text: Roboto Slab
    code: Roboto Mono
  logo: img/logo.png 
markdown_extensions:
  - admonition
  - pymdownx.details
  - pymdownx.superfences
  - pymdownx.highlight:
      anchor_linenums: true
  - pymdownx.inlinehilite:
  - pymdownx.snippets
  - pymdownx.critic
  - pymdownx.caret
  - pymdownx.keys
  - pymdownx.mark
  - pymdownx.tilde
  - attr_list
  - pymdownx.emoji:
      emoji_index: !!python/name:material.extensions.emoji.twemoji
      emoji_generator: !!python/name:material.extensions.emoji.to_svg
  - pymdownx.arithmatex:
      generic: true
  - pymdownx.tasklist:
      custom_checkbox: true

nav:
  - Home: ./index.md
  - Student Agreement: ./studentagreement.md
  - Assignments:
    - 1. Principles and Practices: assignments/week01.md

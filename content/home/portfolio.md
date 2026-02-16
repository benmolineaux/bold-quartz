
---
# A section created with the Portfolio widget.
# This section displays content from `content/chillkatuwe/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: 'Chilkatunge iñchu engu!' 
 #Tüfachi kiñe trokiñ chillka mapudungun mew. Kuyfike ngütram ngeyngün, welu ayukefiyu.
subtitle: 'Kom tüfachi chillka nieyngün *notas* wingkadungun mew. Müley ka kiñe [Trürn’emülwe](Glosario.pdf).'

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: Kom chillka
      tag: '*'
    - name: Reñma mongen
      tag: RM
    - name: L'awen'tun
      tag: LT
    - name: Iyagel
      tag: IYG
    - name: Palin
      tag: palin
    - name: Epew
      tag: epew
    - name: Kawiñ
      tag: kawin
    - name: Ül
      tag: ul
      
design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}

---

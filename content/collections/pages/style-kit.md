---
id: 93c167b9-ba61-40d3-a6c5-f5cef9aa5419
blueprint: page
title: '[Design] Style Kit'
seo_noindex: false
seo_nofollow: false
seo_canonical_type: entry
sitemap_change_frequency: weekly
sitemap_priority: 0.5
updated_by: 441fac1b-bab7-4fa2-8e73-af53be9b8d68
updated_at: 1729759847
page_builder:
  -
    id: m2mytocp
    article:
      -
        type: heading
        attrs:
          level: 2
        content:
          -
            type: text
            text: 'Heading 2'
      -
        type: heading
        attrs:
          level: 3
        content:
          -
            type: text
            text: 'heading 3'
      -
        type: heading
        attrs:
          level: 4
        content:
          -
            type: text
            text: 'heading 4'
      -
        type: heading
        attrs:
          level: 5
        content:
          -
            type: text
            text: 'heading 5'
      -
        type: paragraph
        content:
          -
            type: text
            text: 'paragraph text with '
          -
            type: text
            marks:
              -
                type: bold
            text: bold
          -
            type: text
            text: ', some '
          -
            type: text
            marks:
              -
                type: italic
            text: italics
          -
            type: text
            text: ' and a '
          -
            type: text
            marks:
              -
                type: link
                attrs:
                  href: '#'
                  rel: null
                  target: null
                  title: null
            text: 'text link'
      -
        type: bulletList
        content:
          -
            type: listItem
            content:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Bullet item'
          -
            type: listItem
            content:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Bullet item'
      -
        type: orderedList
        attrs:
          start: 1
        content:
          -
            type: listItem
            content:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Numbered list item'
          -
            type: listItem
            content:
              -
                type: paragraph
                content:
                  -
                    type: text
                    text: 'Numbered list item'
      -
        type: paragraph
      -
        type: blockquote
        content:
          -
            type: paragraph
            content:
              -
                type: text
                text: 'Blockquote text'
      -
        type: set
        attrs:
          id: m2n2al1c
          values:
            type: pull_quote
            size: lg
            quote: 'Pull quote text for styling the thing (set to LG size'
            author: 'Author citation'
      -
        type: paragraph
        content:
          -
            type: text
            text: 'More text'
      -
        type: set
        attrs:
          id: m2n2bhdu
          values:
            type: image
            image: a-peak.jpg
            size: md
            caption: Caption
      -
        type: set
        attrs:
          id: m2n2bqx3
          values:
            type: buttons
            buttons:
              -
                id: m2n2brte
                label: 'This is a button'
                link_type: url
                target_blank: false
                url: '#'
                button_type: button
              -
                id: m2n2c2tk
                label: 'This is an inline button'
                link_type: url
                target_blank: false
                url: '#'
                button_type: inline
    type: article
    enabled: true
---

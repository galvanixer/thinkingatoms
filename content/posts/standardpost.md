---
title: "Standard Post"
date: 2024-11-15
draft: false
postcover:
    image: "images/thumbs/single/single-post-2100.jpg"
    imagealt: "Leaf"
author_name: "Urvashi Sharma"
author_avatar: "images/avatars/user-06.jpg"
author_url: "#"
categories: ["Standard"]
tags: ["orci", "lectus", "varius", "turpis"]
excerpt: "This is one of the finest blogs I have written. It will change the world and you will see it for sure. Read it and change your life."
---

Duis ex ad cupidatat tempor Excepteur cillum cupidatat fugiat nostrud cupidatat dolor sunt sint sit nisi est eu exercitation incididunt adipisicing veniam velit.
You can use either this:
![Sample Image](/images/sample-1050.jpg)

Or this:

{{< imgset
    src="/images/sample-1050.jpg"
    srcset="/images/sample-2100.jpg 2100w, /images/sample-525.jpg 525w"
    sizes="(max-width: 2100px) 100vw, 2100px"
    alt="An example image"
    caption="This is an image with srcset and caption."
>}}


## Large Heading
### Smaller Heading
Harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta 
nobis est eligendi optio cumque nihil impedit quo minus [omnis voluptas assumenda](http://#)  id quod maxime placeat facere possimus, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et.

### Lead Paragraph
{{< lead >}}
Harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta. 
{{< /lead >}}

### Small Print
{{< small >}}
Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec libero.
{{< /small >}}

### Blockquote
> For God so loved the world, that he gave his only Son, that whoever believes in him should not perish but have eternal life. For God did not send his Son into the world to condemn the world, but in order that the world might be saved through him.  
> -- John 3:16-17 ESV

{{< blockquote_style1 cite="John 3:16-17 ESV">}}
For God so loved the world, that he gave his only Son, that whoever believes in him should not perish but have eternal life. For God did not send his Son into the world to condemn the world, but in order that the world might be saved through him.
{{< /blockquote_style1 >}}


### Drop Caps
{{< dropcaps >}}
Far far away, behind the word mountains, far from the countries Vokalia and Consonantia,
there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the
Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the 
necessary regelialia. Morbi tincidunt, orci ac convallis aliquam, lectus turpis varius lorem, 
euposuere nunc justo tempus leo. Donec mattis, purus nec placerat bibendum, dui pede condimentum odio, 
ac blandit ante orci ut diam. Cras fringilla magna. Phasellus suscipit, leo a pharetra condimentum, 
lorem tellus eleifend magna, eget fringilla velit magna id neque.
{{< /dropcaps >}}

### Paragraph and Image
<figure>
<img width="120" height="120" class="h-pull-left" alt="sample-image" src="/images/sample-image.jpg">
</figure>
Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec libero. Suspendisse bibendum.Cras id urna. Morbi tincidunt, orci ac convallis aliquam, lectus turpis varius lorem, eu posuere nunc justo tempus leo. Donec mattis, purus nec placerat bibendum, dui pede condimentum odio, ac blandit ante orci ut diam. Cras fringilla magna. Phasellus suscipit, leo a pharetra condimentum, lorem tellus eleifend magna, eget fringilla velit magna id neque posuere nunc justo tempus leo. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec libero. Suspendisse bibendum.Cras id urna. Morbi tincidunt, orci ac convallis aliquam, lectus turpis varius lorem, eu posuere nunc justo tempus leo. Donec mattis, purus nec placerat bibendum, dui pede condimentum odio, ac blandit ante orci ut diam. Cras fringilla magna. Phasellus suscipit, leo a pharetra condimentum, lorem tellus eleifend magna, eget fringilla velit magna id neque posuere nunc justo tempus leo. 

### Code Block
{{< codeblock lang="css" >}}
    code {
        font-size: 1.4rem;
        margin: 0 .2rem;
        padding: .2rem .6rem;
        white-space: nowrap;
        background: #F1F1F1;
        border: 1px solid #E1E1E1;    
        border-radius: 3px;
    }
{{</codeblock >}}
### Strong and Emphasized Text
A [link](#), 
<abbr title="this really isn't a very good description">abbreviation</abbr>, 
**strong text**, 
*em text*, 
~~deleted text~~, 
and <mark>this is a mark text.</mark>
<code>.code</code>.

### Pull Quote
{{< pullquote cite="Judah Smith" >}}
When you look in the eyes of grace, when you meet grace, 
when you embrace grace, when you see the nail prints in 
grace’s hands and the fire in his eyes, when you feel his 
relentless love for you - it will not motivate you to sin. 
It will motivate you to righteousness.
{{< /pullquote >}}

### Example Lists
1. Here is an example
2. of an ordered list.
3. A parent list item.
   - one
   - two
   - three
4. A list item.

- Here is an example
- of an unordered list.

### Definition Lists
##### a) Multi-line Definitions (default)

**This is a term**  
: this is the definition of that term, which both live in a `dl`.

**Another Term**  
: And it gets a definition too, which is this line  
: This is a 2<sup>nd</sup> definition for a single term. A `dt` may be followed by multiple `dd`s.


### Skill Bars
{{< skillbars >}}
    {{< skillbar skill="HTML" percent="90" >}}
    {{< skillbar skill="CSS" percent="85" >}}
    {{< skillbar skill="Javascript" percent="70" >}}
    {{< skillbar skill="PHP" percent="95" >}}
    {{< skillbar skill="Wordpress" percent="75" >}}
    {{< skillbar skill="Node JS" percent="90" >}}
{{< /skillbars >}}

### Stats Tabs 
{{< statstabs >}}
    {{< statstab url="#0" value="1,234" label="Peter" >}}
    {{< statstab url="#0" value="567" label="James" >}}
    {{< statstab url="#0" value="23,456" label="John" >}}
    {{< statstab url="#0" value="3,456" label="Andrew" >}}
    {{< statstab url="#0" value="456" label="Philip" >}}
    {{< statstab url="#0" value="26" label="Matthew" >}}
{{< /statstabs >}}


### Tables
{{< table >}} 
| Name                | Age | Sex    | Location     |
|---------------------|-----|--------|--------------|
| William J. Seymour  | 34  | Male   | Azusa Street |
| Jennie Evans Moore  | 30  | Female | Azusa Street |
{{< /table >}}

### Callouts

{{< callout_heading color="red" title="Fun Fact" iconstyle="duotone" icon="watch">}}
Blood, often associated with its characteristic red color, exhibits a fascinating array of hues across the animal kingdom due to variations in oxygen-carrying molecules and their structures. In humans and most vertebrates, blood appears red because of hemoglobin, an iron-based protein that binds oxygen. Oxygenated blood is bright red, while deoxygenated blood takes on a darker, maroon shade. However, not all creatures rely on hemoglobin. Some mollusks and arthropods, such as crabs and octopuses, have blue blood due to hemocyanin, a copper-based molecule that transports oxygen. Certain species of marine worms, like peanut worms, have violet blood, a result of hemerythrin, another oxygen-carrying protein. Even more intriguing is the green blood of some lizards in New Guinea, which is caused by high levels of biliverdin, a bile pigment. Each blood color serves unique physiological roles, highlighting the incredible diversity of adaptations in nature.
{{< /callout_heading >}}

{{< callout color="yellow">}}
Blood, often associated with its characteristic red color, exhibits a fascinating array of hues across the animal kingdom due to variations in oxygen-carrying molecules and their structures. In humans and most vertebrates, blood appears red because of hemoglobin, an iron-based protein that binds oxygen. Oxygenated blood is bright red, while deoxygenated blood takes on a darker, maroon shade. However, not all creatures rely on hemoglobin. Some mollusks and arthropods, such as crabs and octopuses, have blue blood due to hemocyanin, a copper-based molecule that transports oxygen. Certain species of marine worms, like peanut worms, have violet blood, a result of hemerythrin, another oxygen-carrying protein. Even more intriguing is the green blood of some lizards in New Guinea, which is caused by high levels of biliverdin, a bile pigment. Each blood color serves unique physiological roles, highlighting the incredible diversity of adaptations in nature.
{{< /callout >}}
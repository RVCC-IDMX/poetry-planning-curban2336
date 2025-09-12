# Planning Document Template

**Student Name:** [Christopher]  
**Date Completed:** [2025-09-11]  
**AI Tool Used:** [ChatGPT]

## My chosen poem

**Poem:** "[Stopping by Woods on a Snowy Evening]" by [Robert Frost]

**Public domain verification:**
``` text
[Despite Robert Frost only dying in 1963, several sources assert that this poem is in the public domain. The Columbian and The Smithsonian both marked January 1, 2019 as the date in which any of Frosts works from 1923 and back entered the public domain.]
```

**Why I chose this poem:**
``` text
[The poem is one I have read before. I find it interesting and not as complex as other poems. This makes it perfect for almost any display structure on the webpage and accommodating for almost any styling choices I might make. Not only that, but this poem is also relatively short, meaning it will require less effort to optimize for screen sizes of varying dimensions. The poem itself is also visually descriptive, giving me plenty of visual aids to work with to really make the webpage pop with color and detail.]
```

**Brief description for design purposes:**
``` text
[It has a little bit of an eery evocation to it. The poem described a rider stopping by a deep woods on a snowy afternoon. The horse he rides is nervous and confused about the reason for the stop. It ends with the rider expressing a promise he must keep, and the miles he must ride before he can sleep. There is a lot of great imagery that can be used here to fashion a good webpage design.]
```

## HTML guidelines

Based on my AI conversations, here are my simple guidelines for structuring this poem:

**Document structure:**
- [ ] Main heading: [Stopping by Woods on a Snowy Evening]
- [ ] Poem container: [I will be using Div. According to my AI assitant: it's scalable, clean, flexible, and despite not being semantic it can become so with proper class assignment.]
- [ ] Stanza handling: [Every 4 lines of the poem will be marked as a stanza, making 4 stanzas total]
- [ ] Line breaks: [Each line will be its own span within the div container for the stanza.]
- [ ] Author attribution: [Author will be attributed immediately after the title of the poem in an h2]

**Semantic elements to use:**
- [ ] Header: [Just the title of the webpage]
- [ ] Main: [The h1 and h2 titles for the title of the poem and the name of the author. After that, the poem in the four stanza breakdown. ] 
- [ ] Footer: [The year the poem is first published and the declaration of the poems public domain status]
- [ ] [There will be img usage before the poem and between the stanzas to give the poem a better reader experience.]

**Accessibility considerations:**
- [ ] Heading hierarchy: [This poem will only have two headers: an h1 for the title of the poem, and an h2 for the accredation of the author]
- [ ] [Going to add alt text to each image for accessibilty. Need to make sure there is good color contrast for this webpage. Considering adding ARIA for more generalized accessibility for screen readers. Choose optimized typography for legibility. Finally, make sure the website looks good zoomed in with a focus section to the CSS.]

## CSS guidelines

Based on my AI conversations, here are my simple design guidelines:

**Colors:**
- Background: [Soft snowy white: #f5f7fa]
- Text: [Near-Black: #1c1c1c]
- Accent color: [Deep cool blue: #003366]
- Why these colors: [These colors are not only extremely legible with their contrast, but they also reflect the snowy nature of the poem.]

**Typography:**
- Heading font: [Merriweather] - Why: [A classic serif font, with a naturally heavy letter weight, making it perfect as the title font for this poem webpage.]
- Body/poem font: [Literata] - Why: [A classic serif font, easy to read and distinct letter structure. Less weight to the characters then Merriweather so it will be perfect for a body text.]
- Font sizes: [h1 will be anywhere from 32px to roughly 56px. The idea is to use rem units and clamp the font sizes to make a fluid scaling between screen sizes but still keep the relative sizing for the structure of the webpage. h2 will range between 20px to 32px, and the body text will range 16px to 18px]

**Layout and spacing:**
- Content width: [Content area will be 800px wide by AI recommendation]
- Stanza spacing: [Roughly 2.5 rem between each stanza]
- Overall feel: [Wintery, with a slighly ominous tone to it.]

**Simple responsive plan:**
- Mobile: [Font sizing and content spacing will adjust for smaller screen sizes(accommodating landscape view)]
- Desktop: [Larger font sizing and wider content spacing to leave as little empty space as reasonably possible. The primary goal is to make it look good, after all]

## Key AI conversations and discoveries

### What worked well
**Best prompt and response:**
``` text
[I will be using "Stopping by Woods on a Snowy Evening" for this project, thank you. What do you think would be a good HTML format for this?]
```

**Why this worked:**
``` text
[The AI went into a pretty comprehensive breakdown of what it thought the HTML format should look like. This springboarded more specific questions that allowed me to really nail down what would work best for the webpage application. ]
```

### What surprised you
**An AI limitation you discovered:**
``` text
[Example: AI makes really long winded responses that make scrolling back through conversations a major hassle]
[Example: AI doesn't always answer the question directly, sometimes involving topics that I didn't ask about at all]
[Example: AI forgot about design choices it suggested and spoke as if I was the one to choose them]
```

**How you worked around it:**
``` text
[I asked the AI to keep responses shorter to deal with the complex response issues. I then asked more specific questions that the AI couldn't answer by adding extra topic on top of.]
```

## Ready to build?

**Do you feel prepared to start coding your poetry website?** [Yes]

**What are you most confident about?**
``` text
[Most of the plan feels pretty solid. The color scheme and most of the styling is pretty straight forward. The HTML structure is also pretty straightforward. There is also just enought wiggle room in the specifications for me to experiment and find something really special.]
```

**What might you need to figure out as you go?**
``` text
[I really need to nail down the specifics on the screen size adaptions as well as any accessibility additions that will need to be made. I will also need to collect a good assortment of pictures for a better reader experience, maybe also add a hover effect to change text color for lines the cursor is over to keep track of where you are.]
```

**Next step:** Start building your poetry website using these guidelines as your reference!
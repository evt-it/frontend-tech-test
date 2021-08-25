# frontend-tech-test

## Task

Build a SPA using ReactJS that does the following:

- display a list of heroes' names
- have a search box on top of the page - enter a keyword it will be matched against all data relevant to the hero and only matched names will show up - remove the keyword all names should show up
- click on a name will go to sub page `/<hero name>`, and will display the hero's bio and a list of their nemesis - this time the search box on top will only match on the nemesis
- click on a nemesis's name will go to sub page `/<hero name>/nemesis/<nemesis-name>`, and will display the nemesis's bio - this time the search box shall disappear
- display a breadcrumb at the top of the page so we can easily navigate back to the previous 2 pages

### Key Points

- Single page app with working path (e.g. `/spider-man/` will only show the Spider-man page)
- Unit test for search function (choose your own test framework)
- Prepare a readme to explain how to build/run/test the app


### Data

Data is provided here, feel free to use it (or find some more of your own)

```
[
    {
        "name": "Spider-man",
        "real name": "Peter Parker",
        "hobby": "Mary Jane",
        "power": [
            "Superhuman strength", 
            "speed", 
            "reflexes", 
            "agility", 
            "coordination and balance", 
            "Ability to cling to solid surfaces", 
            "Accelerated healing", 
            "Genius level intellect", 
            "Proficient scientist and engineer", 
            "Precognitive spider-sense ability", 
            "Utilizing wrist-mounted web-shooters"
        ],
        "nemesis": [
            {
                "name": "Chameleon1",
                "bio": "A master of disguise who can make himself look like anybody",
                "first appearance": "#1 (March 1963)"
            },
            {
                "name": "Vulture",
                "bio": "An inventor who created mechanical wings that allow him to fly and grant him superhuman strength",
                "first appearance": "#2 (May 1963)"
            },
            {
                "name": "Doctor Octopus",
                "bio": "Originally a brilliant scientist, his greatest invention, a set of metallic limbs, became fused to his body by an accident which caused his insanity. He has telepathic control of these arms, which are strong enough to physically hurt Spider-Man.[16] While Doctor Octopus is regarded as one of Spider-Man's archenemies, he also been portrayed as an antihero, and even starred in his own comic book storyline that saw him becoming a superhero called the Superior Spider-Man after the original Spider-Man's death.",
                "first appearance": "#3 (July 1963)"
            },
            {
                "name": "Sandman",
                "bio": "Once a small-time crook, he became a supervillain after his body merged with sand which he can manipulate in many ways, such as shapeshifting, increasing his density and strength to lift up to 85 tons, and creating dust storms from his body.",
                "first appearance": "#4 (September 1963)"
            }
        ]
    },
    {
        "name": "Wonder Woman",
        "real name": "Princess Diana of Themyscira",
        "hobby": "Steve Trevor",
        "power": [
            "masterful athlete", 
            "acrobat", 
            "fighter", 
            "strategist",
            "superhuman strength",
            "nigh-invulnerability",
            "speed",
            "flight",
            "fast healing and semi-immortality"
        ],
        "nemesis": [
            {
                "name": "The Angle Man",
                "bio": "Originally a clever schemer who \"knew all the angles\" known as Angelo Bend, the updated Angle Man possesses an object known as an Angler which can alter objects and locations according to the holder's wishes, sometimes defying gravity or through teleportation. The Angle Man was created as a recurring foil for Wonder Woman during the 1950s and 1960s",
                "first apperance": "Wonder Woman #62 (November/December 1953)"
            },
            {
                "name": "The Cheetah",
                "bio": "Byrna Brilyant is a small town teacher and scientist who uses her late father's invention of \"blue snow\" for self-gain. Byrna disguised herself and unleashed the petrifying power of the blue snow upon the farming community of Fair Weather Valley, demanding each farmer's \"life savings\" in return for the chemical antidote that will free the crops, livestock, and people from the snow's effects. She was discovered in her mountain sanctuary by Wonder Woman, who forces her to defrost the valley.",
                "first appearnce": "Wonder Woman #6 (October 1943)"
            },
            {
                "name": "Circe",
                "bio": "Circe is based on the Greek mythological character of the same name. A witch and sorceress of vast power, specializing in illusion and transformation spells, Circe became one of Wonder Woman's most formidable foes in the Post-Crisis DC continuity, and even triggered a War of the Gods.",
                "first appearance": "Wonder Woman #37 (September/October 1949)"
            },
            {
                "name": "Deimos",
                "bio": "Deimos is the God of Dread and the son of Ares and Aphrodite. He planned to ignite a war between the United States and the Soviet Union, though his plans were thwarted by Wonder Woman. After the events of DC Rebirth, Deimos and his brother Phobos took the appearance of handsome twins and plotted to find Themyscira so that they could free their father Ares. Their actions led to the formation of Godwatch.",
                "first appearance": "Wonder Woman #183 (August 1969)"
            },
            {
                "name": "Doctor Cyber",
                "bio": "Wonder Woman #179 (November–December 1968)",
                "first appearance": "A female criminal mastermind and head of an international crime syndicate, Doctor Cyber was Wonder Woman's nemesis during a period when she had given up her Amazon powers and become a white-costumed karate expert. During an early battle, Cyber's face was horribly burned. Vowing revenge for her ruined beauty, she became obsessed with having Wonder Woman's face removed and surgically grafted on her own. She also teamed up with Batman foe Doctor Moon in this period. Post-DC Rebirth, Doctor Cyber is the computerized assistant of Veronica Cale and a member of the organization Godwatch."
            }
        ]
    }
]
```

## Technologies

### Required:

- ReactJS
- Bootstrap 4 or 5
- Less or SASS

### Optional:
- npm or yarn whichever you prefer
- redux or hook

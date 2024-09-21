# The Attributes Method

When trying to create your Lorebook, someone may have suggested the "Attributes Method". We mentioned it in the Starter guide. This page will explain it in further detail, so that you can feel more confident creating your entries.

## The purpose of Attributes

The idea behind the Attributes method is to simplify how you organize the description of important elements in your story. While Attributes were originally designed with characters in mind, **Attributes can be used for anything.** By using Attributes, you can use the training of NovelAI's models to your advantage, as it is used in their finetune material.

## Building Attribute entries

An Attributes entry is assembled from three elements:

• **Separators**, usually four dashes (----), **followed by a line break**, are positioned at the beginning and end of the entry to signal that it contains "data" as opposed to story. The final entry does not need one, as you'll likely have a dinkus around there instead.

• **Title and short description**, immediately after the starting separator. Start with the name of the character or element, and a very simple description. e.g `Shadowheart, follower of Shar`

• **Attributes**, which are a *header*, followed by a *colon* (:), and one or multiple sentences. A single attribute is a **single paragraph**, with each attribute starting on a new line. Attribute titles can be one word, multiple words, or words with an additional adjective, e.g `Beliefs (hidden):`.

### Ordering Attributes

Attributes can be in any order, as long as you keep it consistent between entries of the same type. However, some entries are notable exceptions.

Positioned at the **beginning** of the entry, immediately after the title, should be:

• `AKA:` which provides alternate names for the element. This is also where alternate Lorebook **keys** should be specified.

• `Type:` which specifies what type of element it is. (e.g person, place, faction; just like in the Lore Generator's categories, but you can improvise.)

• `Setting:` which specifies which setting the element is from, in case you are doing a crossover story, or want to specify the tone of the entry.

Positioned at the **end** of the entry, before the closing separator, should be:

• `Summary:` which provides a short blurb about the entry.

• `Quote:` which gives example dialogue for elements that speak, multiple can be provided.

• A prose block can be added at the very end of the entry as well, if you feel further detail is needed.

### Writing Attributes

Attributes can be written in any style you like, though it is important to focus on making your entries **stylistically consistent**, as well as **containing clear, easily understood information**. Its purpose is to influence generations, so make sure you convey your ideas in a way that the model can understand.

As a default, write attributes as **a list of individual words** separated by **commas**, with the intent of conjuring the correct "vibe" for that attribute. More verbose entries can lead to more verbose prose in response, but this will impact your token budget.

For convenience, you can set up a blank entry that has no keys and only contains the starting separator and headers you frequently use. **It is not necessary to put in an ending separator**, as it will automatically be included when multiple entries are present back-to-back. Once done, you can duplicate and fill the entry as you create new elements.

# Attributes Entry Example

## Level I - Basic Attributes

Let us start with an entry that only has the bare minimum information needed. We will add to it gradually as we go through examples. For now, we will just have a generic protagonist.

```
----
Parker, author avatar
Gender: Male
Age: Adult
Appearance: brown hair, stubble, toned build
```

This should be enough to describe a character. Most background characters can make do with this much. If you need something more advanced...

## Level II - Personality

Perhaps we want this character to act in a specific way. Let's do this through their personality. Why not give them a job, and a goal to strive for as well?

```
----
Parker, author avatar
Gender: Male
Age: Adult
Appearance: brown hair, stubble, toned build
Personality: creative, sassy, audacious, hard-working
Occupation: writer
Goals: Write 10 best-sellers.
```

Of course we can always push this further if needed.

## Level III - Reputation and Factions

Let's say our writer is a bit of a celebrity, and is a major figure for a group that also enjoys some positive reputation.

```
----
Parker, author avatar
Gender: Male
Age: Adult
Appearance: brown hair, stubble, toned build
Personality: creative, sassy, audacious, hard-working
Occupation: writer
Group: Powerful Prose Creatives (a well-respected online publisher)
Rank: Founder
Reputation: known for his popular saucy novels, translated in 20 languages.
Goals: Write 10 best-sellers.
```

Want to push this further? There is a lot more that can be said.

## Level IV - Preferences and Relations

Let's give Parker a bit of depth by detailing the people around him, and what he enjoys (and dislikes) in life.

```
----
Parker, author avatar
Gender: Male
Age: Adult
Appearance: brown hair, stubble, toned build
Personality: creative, sassy, audacious, hard-working
Likes: his typewriter, challenging himself
Dislikes: ink stains, boring prose
Occupation: writer
Group: Powerful Prose Creatives (a well-respected online publisher)
Rank: Founder
Reputation: known for his popular saucy novels, translated in 20 languages.
Goals: Write 10 best-sellers.
Friends: Nigel, Armand
Family: a wife (Jennifer), two daughters (Clara, Diane)
```

At this point, you should be feeling pretty confident. Remember that **basically any header works**, as long as it makes sense and the description fits what you chose.

## Level V - Full Fantasy Entry

Let's change gears and design a character for an existing Fantasy setting. Here, we will be using different headers to present someone that belongs to a role-playing game setting.

```
----
Yanelie, elven adventuress
AKA: Yana
Type: Character
Gender: Female
Species: High Elf
Setting: The Elder Scrolls 
Age: Adult
Appearance: long blonde hair, teal eyes, pale skin, slender build
Personality: brave, perceptive, prudent
Flaws: overzealous, introverted
Class: Ranger
Equipment: longbow, leather armor
Abilities: low-level magic, speak with animals
Skills: trapping, mapping, hunting
Group: Adventurers' Guild
Rank: Journeyman
```

Note the addition of the new fields, such as **setting**, **flaws**,  and the **class, equipment, abilities and skills**.
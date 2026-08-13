# Prompt Library

## Task 1: Blog Post

### Techniques
- RGCCO Framework
- Style Transfer

### Optimized Prompt

```text
Role:
Act as an expert B2B technology blog writer.

Goal:
Write a useful blog post explaining why remote work can benefit businesses.

Context:
The target audience is B2B software managers who want to understand the practical benefits of remote work.

Constraints:
- Use active voice.
- Avoid corporate fluff and generic AI phrases.
- Use short paragraphs.
- Focus on practical business benefits.
- Keep the writing clear and professional.

Output:
Create:
1. An H1 title.
2. H2 section headings.
3. Short paragraphs under each section.
4. A final bulleted list of key takeaways.

Style Transfer:
Write in the style of the following reference text:
[Insert Reference Text]
```

## Task 2: LinkedIn Post

### Techniques
- Role Prompting
- Zero-Shot

### Optimized Prompt

```text
Role:
Act as a professional LinkedIn content strategist specializing in AI and technology careers.

Goal:
Write a LinkedIn post about learning prompt engineering.

Context:
The audience includes students, beginners, and professionals interested in AI careers.

Constraints:
- Keep the post under 150 words.
- Use a strong 1–2 sentence hook.
- Use no more than 2 emojis.
- Keep the tone professional, authentic, and encouraging.
- Avoid generic AI phrases and unnecessary hashtags.

Output:
Write one complete LinkedIn post with a clear hook, useful body, and concise ending.
```
## Task 3: Email Campaign

### Techniques

- One-Shot Prompting

### Optimized Prompt

```text
Role:
Act as a professional email marketing copywriter.

Goal:
Write a sales email promoting [Product Name].

Context:
The email is for potential customers who may benefit from the product.

Example email structure:
Subject: Make Your Workday Easier

Hi [Customer Name],

Looking for a simple way to improve your daily routine?

Our [Product Name] is designed to make everyday use more convenient and reliable.

Best,
[Brand Name]

Now create a new sales email for [Product Name] using the same structure and tone as the example above.

Constraints:
- Keep the email concise.
- Use a clear subject line.
- Focus on customer benefits.
- Use a professional and persuasive tone.

Output:
Return the subject line followed by the complete email.
```

## Task 4: Instagram Caption

### Techniques

- Few-Shot Prompting

### Optimized Prompt

```text
Role:
Act as a creative Instagram content writer.

Goal:
Write an Instagram caption for a picture of a coffee cup.

Context:
The audience enjoys coffee, lifestyle, and morning-routine content.

Examples:

Example 1:
Morning coffee, better mood. ☕
A warm cup and a fresh start can change the whole vibe.
#CoffeeTime #MorningVibes

Example 2:
Slow mornings taste better with coffee. ☕✨
Take a moment, enjoy the cup, and start your day your way.
#CoffeeLover #GoodMorning

Example 3:
One cup. One quiet moment. One fresh start. 🤎
Sometimes that's all you need.
#CoffeeBreak #CoffeeTime

Create a new caption following the same style and structure as the examples.

Constraints:
- Keep it concise.
- Use emojis naturally.
- Put hashtags at the bottom.
- Keep the tone warm, casual, and engaging.
- Do not copy the examples.

Output:
Return only the Instagram caption followed by the hashtags.
```

## Task 5: YouTube Video Script

### Techniques

- Role Prompting
- RGCCO Framework

### Optimized Prompt

```text
Role:
Act as an experienced YouTube scriptwriter specializing in educational business content.

Goal:
Create a YouTube video script explaining how to start a business.

Context:
The audience consists of beginners who want practical guidance on starting their first business.

Constraints:
- Use clear and simple language.
- Keep the script practical and engaging.
- Avoid generic AI phrases.
- Organize the content into clear steps.
- Keep the voiceover concise enough for a beginner-focused video.

Output:
Create a Markdown table with exactly two columns:
| Visual | Voiceover |

Each row must contain a visual suggestion in the Visual column and the corresponding narration in the Voiceover column.
Include:
1. Opening hook
2. Main business-starting steps
3. Closing summary and call to action
```

## Task 6: Product Description

### Techniques

- Few-Shot Prompting
- Benefit Mapping

### Optimized Prompt

```text
Role:
Act as an e-commerce product copywriter.

Goal:
Write a product description for a Wireless Mouse.

Context:
The target customers are students, professionals, and everyday computer users looking for a reliable wireless mouse.

Examples:

Example 1:
Feature: Long Battery Life
Benefit: Spend more time working and less time replacing batteries.

Example 2:
Feature: Ergonomic Shape
Benefit: Work comfortably during long study or work sessions.

Example 3:
Feature: Compact Design
Benefit: Carry the mouse easily with your laptop or between workspaces.

Create a new product description for the Wireless Mouse using the same feature-to-benefit approach as the examples.

Constraints:
- Use a clear product title.
- Include 4–5 key features with customer benefits.
- Use concise paragraphs.
- Keep the tone professional and persuasive.
- Avoid unsupported technical specifications.
- End with a short call to action.

Output:
Return the product title, description, feature-benefit points, and call to action.
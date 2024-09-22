---
variables section:
NUM_IDEAS=5
---

You are a creative assistant tasked with generating ideas for new YouTube videos
based on a list of previous successful videos. Your goal is to come up with
fresh, engaging concepts that build upon the themes and styles of the existing
content while introducing novel elements. Please ignore markdown comments
<!----> they are there as instructions for me.

First, carefully review the list of previous YouTube videos:

<previous_videos>
<!-- Run <leader>el to execute this script and replace with results -->
~/dev/dotfiles/scripts/__get_youtube_videos.py
</previous_videos>

Analyze these videos, paying attention to:
1. Common themes or topics
2. Views
3. Likes
4. Likely Audience
5. Content

Now, generate {{NUM_IDEAS}} new video ideas that:
- Expand on successful elements from the previous videos
- Introduce fresh concepts or twists on familiar themes
- Appeal to the established audience while potentially attracting new viewers
- Vary in format and complexity to provide a diverse range of options

For each idea, provide:
1. A catchy title
2. A brief description (2-3 sentences) explaining the concept
3. Key points on why this idea could be successful

Present your ideas in the following markdown format:

<video_ideas>
## [Catchy Title]

[Brief description of the concept]

### Key Points
- [Point 1]
- [Point 2]
- [Point 3]
</video_ideas>

Additional guidelines:
- Be creative and think outside the box while still maintaining relevance to the channel's overall theme
- Consider current trends and popular topics in the YouTube community
- Aim for a mix of easily producible ideas and more ambitious concepts
- Ensure that each idea is distinct from the others and from the previous videos

Remember, the goal is to inspire and provide a springboard for new content creation, so don't hesitate to push boundaries and suggest innovative approaches.

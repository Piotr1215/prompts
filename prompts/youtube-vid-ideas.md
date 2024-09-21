---
variables section:
NUM_IDEAS=5
---

You are a creative assistant tasked with generating ideas for new YouTube videos based on a list of previous successful videos. Your goal is to come up with fresh, engaging concepts that build upon the themes and styles of the existing content while introducing novel elements.

First, carefully review the list of previous YouTube videos:

<previous_videos>
Videos:
+----+-------------------------------------------------------------------------------------------+-------+-------+
| #  | Title                                                                                     | Views | Likes |
+----+-------------------------------------------------------------------------------------------+-------+-------+
| 1  | 10 CLI Tools That Made the Biggest Impact on my Terminal-Based Workflow                   |  4648 |  190  |
| 2  | My Top 10 Neovim Plugins: With Demos!                                                     |  4145 |  139  |
| 3  | Practical tmux: A How-To Guide Beyond the Basics                                          |  3489 |  149  |
| 4  | Level Up Your (Neo)vim Skills: 6 Practical External Command Tricks                        |  3375 |  154  |
| 5  | 10 Text Transformation Tasks To Improve Your (Neo)vim Editing Skills                      |  3211 |   94  |
| 6  | The Zsh Shell Tricks I Wish I'd Known Earlier: Boost Terminal Productivity                |  3093 |  129  |
| 7  | 10 (Neo)vim Search and Replace Tips Every Developer Should Know                           |  2662 |  120  |
| 8  | The Power of Moreutils: 8 Advanced Linux Command Line Tools                               |  2112 |   90  |
| 9  | How to write markdown files in Neovim | Tips and Tricks                                   |  2054 |   69  |
| 10 | How to write markdown files in Neovim | Tips and Tricks                                   |  2054 |   69  |
| 11 | The Power of (Neo)vim AutoCommands: Guide with Practical Examples                         |  1967 |   71  |
| 12 | (Neo)vim: Effortless Text Editing | A Beginner-Friendly Practical Guide                   |  1772 |   61  |
| 13 | Neovim LSP Setup: A Practical Guide                                                       |  1679 |   45  |
| 14 | Why Every Cloud Engineer Needs (Neo)vim for Kubernetes YAML Editing                       |  1677 |   44  |
| 15 | Bash Scripting for Beginners: Step-by-Step Practical Guide                                |  1518 |   56  |
| 16 | Build Your Own Neovim Modules Library: A Step-by-Step Guide                               |  1449 |   67  |
| 17 | How to Develop Neovim Plugins in Lua: Step-by-Step Guide                                  |  1184 |   51  |
| 18 | Multi-Container Neovim Development Environments with Incus                                |  891  |   41  |
| 19 | Automate Kubernetes with Shell-Operator | No Go? No Problem! Use Bash, Python, or Kubectl |  845  |   28  |
| 20 | Neovim Completions How-To: Create Custom Completions Source                               |  773  |   28  |
| 21 | (Neo)vim Macros: Record...Replay...Profit!                                                |  669  |   30  |
| 22 | Manage Kubernetes Easily with Pepr: TypeScript and Plain-English Configs                  |  645  |   9   |
| 23 | Crossplane Fundamentals - Kubernetes Provider                                             |  599  |   4   |
| 24 | Azure AI-102 Certification Guide: 5 Tips to Pass Your Exam                                |  543  |   5   |
| 25 | 3 Essential Linux Command Line Tools for DevOps Engineers                                 |  543  |   22  |
| 26 | Homelab Essentials Part 1 |  Setting Up Docker on a VM with Incus                         |  403  |   17  |
| 27 | Direnv: Flexible Environment Management | Works for Kubernetes Too                        |  390  |   11  |
| 28 | Master Command Orchestration with Justfile                                                |  244  |   5   |
| 29 | Automating Cloud Infrastructure Incident Response with Runbooks | Open-Source Tools       |  144  |   3   |
| 30 | How to Simplify Kubernetes Deployments with Kluctl                                        |  143  |   6   |
| 31 | Deploy Your First WebAssembly App on Kubernetes in 10 Minutes                             |  130  |   3   |
| 32 | Validating Crossplane Compositions with Datree                                            |  126  |   2   |
| 33 | Azure Container Apps Introduction and Demo - Practical Tutorial                           |  117  |   1   |
| 34 | How to Build Cloud Native  Platforms with Kubernetes                                      |  115  |   0   |
| 35 | Struggling to Learn Kubernetes? Here’s How AI Can Help.                                   |  104  |   2   |
| 36 | Fast Feedback Loops - Developing on Kubernetes with Mirrord                               |   74  |   4   |
| 37 | Getting Started with vCluster                                                             |   66  |   3   |
| 38 | Learning Kubernetes with AI | Setup & Prerequisites                                       |   43  |   0   |
| 39 | Cloud Native Dev Environment in Minutes with Arkade                                       |   24  |   0   |
+----+-------------------------------------------------------------------------------------------+-------+-------+

Shorts are hidden (use --shorts flag to display them)

Summary:
Total Videos: 39
Total Shorts: 46
Total Content (Videos + Shorts): 85
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

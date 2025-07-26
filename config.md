<!--
Global configuration for Franklin.jl
Used for metadata, site-wide behavior, and deployment settings.
-->

+++
# 👤 AUTHOR INFO
author = "Anas Bouali"

# 🧭 TOC DEPTH: Show up to level 2 headers in the table of contents
mintoclevel = 2

# 🌐 DEPLOYMENT
# Uncomment the line below if deploying to GitHub Pages or another subdirectory
# Example: https://anasxbouali.github.io/academic-site/ → prepath = "academic-site"
# prepath = "yourproject"

# 🧼 IGNORE THESE FILES/FOLDERS WHEN BUILDING
ignore = ["node_modules/", "drafts/", "private/"]

# 🔔 RSS FEED CONFIG (for your blog or publications feed)
generate_rss = true
website_title = "Anas Bouali"
website_descr = "Postdoc Researcher"
website_url   = "https://anasxbouali.github.io/"  # or your custom domain
+++

<!--
LaTeX macros available throughout your site
Define mathematical shorthand or formatting
-->
\newcommand{\R}{\mathbb{R}}
\newcommand{\N}{\mathbb{N}}
\newcommand{\Z}{\mathbb{Z}}
\newcommand{\Q}{\mathbb{Q}}
\newcommand{\C}{\mathbb{C}}
\newcommand{\vect}[1]{\boldsymbol{#1}}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\norm}[1]{\lVert #1 \rVert}
\newcommand{\abs}[1]{\lvert #1 \rvert}

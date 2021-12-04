---
title: 
Robot mouth identification and positioning method

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yike Qiu
  - Han Hao
  - Yizhou Xu
  - Yuxuan Nie
  - Yuhua Jiang
  - Zhoujie Pan
  - Gangtie Zheng

# Author notes (optional)
# author_notes:
# - "First author"
# - "Equal contribution"

date: "2021-06-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: Chinese Patent
publication_short: In *CN Patent*

abstract: "The invention belongs to the technical field of automatic control, and relates to a method for identifying and positioning a human mouth by a robot. The invention identifies and positions key characteristic points of the human face through the depth color image, further calculates and establishes a human mouth coordinate system, calculates the optimal observation position of the camera relative to the human face for active perception, and finally accurately positions the oral cavity space position. The method comprises the following specific steps: acquiring a depth color image of a camera; inputting the color image into an integrated regression tree, and calculating coordinates of the human face characteristic points; coupling the color image and the depth image, and carrying out coordinate transformation to obtain coordinates of the feature points in the camera system; extracting key characteristic points, and calculating to establish a human mouth coordinate system; and moving the mechanical arm according to the optimal observation position of the human mouth coordinate. The method improves the positioning accuracy of the depth camera, and provides a solid foundation for the position judgment, data acquisition and the like of the robot based on the depth camera."

# Summary. An optional shortened abstract.
summary: 

tags: [Medical Robotics]

# Display this page in the Featured widget?
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: ""
#   focal_point: ""
#   preview_only: false
#   filename: featured.jpg

url_pdf: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_poster: ""
url_code: ""
url_source: ""
url_video: ""

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: AIRS

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - AIRS

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

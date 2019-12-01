---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "P4sec -- Securing Networks in the Programmable Data Plane Era"
summary: "
Recent advances in Software Defined Networking (SDN) have expanded our ability to program the network to its data plane. Through domain specific languages like P4, network operators can quickly deploy new protocols on forwarding devices, customize their functionality, and develop innovative services. This flexibility comes however with a cost: network-wide security and correctness properties (e.g., isolation, reachability, etc.) become much harder to ensure, because network behavior is now determined by a combination of the control plane-driven configuration and the data plane program that resides on devices (also called switches). Existing network verification tools, which rely on a fixed, invariant model of the data plane, are inadequate for programmable data planes.

In our P4Sec project, we research new techniques to verify and enforce security properties in data plane networks. The verification techniques we work on extend existing verification tools by automatically generating a data plane model from a P4 program. We also work on adapting existing verification tools to integrate with our dynamically-generated models to verify network configuration updates issued by an SDN controller. We also research novel approaches to ensure that network security properties are satisfied by a network configuration that is based on data plane enforcement. We work to develop an in-line monitor, implemented in the data plane itself, that enforces critical security properties, such as isolation and bandwidth limits, even in the presence of a faulty user data plane program or controller.
"
authors: ["Marinho Barcellos, Kirill Levchenko, Guofei Gu, Bradley Huffake, Weverton Cordeiro, Luciano Paschoal Gaspary, Alberto Egon Schaeffer-Filho, Eduardo Alchieri, Jacir Bordim, João Gondim, Stenio Fernandes"]
tags: []
categories: []
date: 2019-12-01T01:45:06+13:00

# Optional external URL for project (replaces project detail page).
external_link: "http://www.inf.ufrgs.br/p4sec/"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

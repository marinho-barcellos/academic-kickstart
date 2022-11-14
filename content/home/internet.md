+++
widget = "blank"  
# See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 54  # Order that this section will appear.

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "white"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.


[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["15px", "0", "15px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""


title = "Internet Security Research at University of Waikato"
#subtitle = "Internet Scanning Campaign 2022-2023"

+++
{{< figure src="internet/coa-transparent-white.svg" title="">}}

### Why are you receiving connection attempts from this host?

These connections are part of a computer science research project at the [University of Waikato](https://www.waikato.ac.nz/), [School of Computing \& Mathematical Sciences](https://www.cms.waikato.ac.nz/). This research involves making a small number of harmless connection attempts to every publicly accessible computer on the Internet. Similarly to so many other scientific studies, this allows us to methodologically measure the Internet and analyse trends in technology deployment and security.

As part of this specific investigation, every public IP address in the Aotearoa's cyberspace receives a handful of packets on [IANA standard](https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml) and non-standard ports. These consist of conventional connection attempts followed by RFC-compliant protocol handshakes with responsive hosts. We use only tools that have been used in dozens of other scientific studies worldwide (e.g. ZMap, Masscan, ZGrab2 and LZR). We never attempt to exploit security problems, guess passwords, or change device configurations. Furthermore, we only receive data that is publicly visible to anyone who connects to a particular address and port.

This project was ethically approved by the University and follows the widely accepted [best practices for Internet scanning measurements](https://github.com/zmap/zmap/wiki/Scanning-Best-Practices).

### Why are we collecting this data?

The data collected through these connections consists only of information that is already publicly visible on the Internet. It helps us, computer scientists, study the deployment and configuration of network protocols and security technologies. We may be able to detect vulnerable systems and responsibly report the problems to the network operators.

This research helps the scientific community accurately study the Internet. 

### How to opt out of these measurements

The data is sometimes used to detect security problems and to inform operators of vulnerable systems so that they can be fixed. If you opt out of the research, you might not receive these important security notifications.

<!-- If you wish to opt out, you can:
- configure your firewall to drop traffic from the subnet we use for measurements: 171.67.70.0/23; and/or
- ask us via [research-abuse@wand.net.nz](mailto:research-abuse@wand.net.nz) to exclude your network from the set of measurements.  -->
<!-- Please contact us at [research-abuse@wand.net.nz](mailto:research-abuse@wand.net.nz) to discuss any other issues. -->

If you wish to opt out, please use [research-abuse@wand.net.nz](mailto:research-abuse@wand.net.nz) to let us know. We will promptly exclude your network from the set of measurements. 

Dr. Marinho Barcellos  
WAND Research Group   
University of Waikato

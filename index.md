---
layout: default
title: "Thoughts and musings"
permalink: /
---

# Thoughts and musings

Hi there, I'm mechanical engineer by training. I've worked in the architectural glass industry for 10+ years. Check out my [resume here](./resume).

In the last few years, I have been wrangling with heat-transfer performance data for insulated glass units (IGUs). There is a tonne of complexity associated with this that I haven't fully grasp myself, but it seems scientists and regulators may have simplified things too much some areas and introduced unnecessary complications in other area. I intend to document some of these oddities, and hopefully after sufficient thought, we can arrive at better models and tools for designing thermally efficient homes.

One of the unfortunate oversimplifications, at least in Australia, is the selection of the NFRC100-2001 'standard' environmental condition for calculating the heat-transfer coefficient (U-value) of glazing-systems (-18degC outdoor, 21deg indoor). This has lead to widespread adoption of 12mm spacer for IGUs since it 'minimizes' the U-value under NFRC100-2001 conditions. However, -18degC is not a widely encountered outdoor temperature in Australia. If outdoor temperature closer to reality is chosen, the optimal spacer gap would be closer to 14 or 16mm. Here's a web-app you can play with to see how [U-value varies under different environmental conditions and spacer gap](./igu_env_condition).
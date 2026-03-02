---
title: "SAVMO - (Save Me Officer!)"
excerpt: "Car collision classifier using live dash-cam footage <br/><img style='border-radius: 25px;' src='/images/savmo_cover.png'>"
collection: projects
---

The initial version of SAVMO was built in 24 hours as part of the [MAIS HACKS Hackathon](https://devpost.com/software/savmo-save-me-officer), and ended up winning best Hack for Impact!

However, since then I've made heavy modifications to the project, including:

- Implementing multi-processing in order to handle concurrent streams from various users that request live predictions
- Packaging the project in a Docker container, to be potentially hosted on the web
- Updating the model to be packaged with ONNX to be lightweight and be compatible with a multitude of packages
- A UI overhaul

You can find more information on the [github repo](https://github.com/an-andrey/SAVMO-crash-detector)

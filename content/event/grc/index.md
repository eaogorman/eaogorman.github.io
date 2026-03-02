---
title: Hacking neural learning with deep learning: real-time perturbation of high-dimensional song features in the zebra finch

event: Gordon Research Conference and Gordon Research Seminar on the Neural Mechanisms of Acoustic Communication (NMAC GRC and GRS)
event_url: https://www.grc.org/neural-mechanisms-of-acoustic-communication-conference/2024/

location: Newry, ME
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Negative reinforcement of high-dimensional zebra finch song features.
abstract: 'Male zebra finches learn to produce a single, highly stereotyped song and maintain this song over the course of their adult lives using auditory feedback. Such continuous production and evaluation of song is commonly conceptualized as a variant of actor-critic reinforcement learning, requiring the precise coordination of dozens of muscles with millisecond precision. Much of what we know of the underlying algorithms comes through studies of adult male zebra finches adapting to white noise feedback triggered by either high or low-pitch variants of harmonic stack syllables — a single perturbation of a single syllable of a crystallized song. However, zebra finch song is spectrally and temporally rich, with numerous degrees of freedom, and the learning process must tackle this complexity. Thus, to probe the full range of this complexity, new methods are needed for adaptively intervening in the learning process. To this end, we developed a pipeline to quantify and selectively manipulate dimensions of variance within the high- dimensional song space in real time. Using the improv analysis platform, we acquired raw audio from male adults as they practiced in sound-isolated boxes, computed spectrograms from fixed-width segments, and encoded them using a pretrained variational autoencoder (VAE), an unsupervised representation learning method, with resultant latent representations used to trigger delivery of stimuli to the bird. Using asynchronous and parallelized processing, analysis can be performed in 7.396 ms ± 0.917 ms per 120 ms of song, allowing us to update embeddings as frequently as every 10 ms. Even accounting for network latencies, the lag between data acquisition and feedback to the bird is 15.164 ms ± 2.409 ms, well within behaviorally relevant timing. As a result, this pipeline can be used to study adaptations of song in response to algorithmically guided perturbations, allowing us to test fundamental learning reinforcement learning hypotheses in a tractable high-dimensional system.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-22-05T20:10:00Z'
date_end: '2030-22-05T20:20:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - type: code
    url: https://github.com
  - type: slides
    url: https://slideshare.net
  # - type: video
  #   url: https://youtube.com

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - improv-ava
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using the `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to this page bundle and link it using `links: [{ type: slides, url: path/to/file } ]` in front matter
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.

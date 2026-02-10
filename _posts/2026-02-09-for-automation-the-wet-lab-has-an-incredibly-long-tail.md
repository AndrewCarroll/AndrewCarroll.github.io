*Disclaimer: These are solely my views.*

This blog is about how automation of wet lab work will proceed. The concept of an AI lab-in-loop is relevant, but most of the trends and limits are independent of it.

We’re talking science, and science is all about falsifiable predictions. So the core of the blog is: lab automation will occur incrementally in a task-by-task manner for assays of large individual scale. The long tail majority of lab tasks will only be automated around or after when widespread, general skilled task automation occurs (e.g. plumbing, electrical, mechanic).

Lab automation will at the same time provide substantial value for assays run at scale.

## The Long Tail of Wet Lab Work

I want to illustrate this with a story. In the first year of my PhD, I biked to whole foods, bought a fresh coconut, cracked it in the lab, filtered the water, and used it in a protocol.

My advisor suggested we try to watch the process of a plant cell regenerate its cell wall after removal by using a fluorescent carbohydrate binding dye and a labelled protein. But plant cells really don’t like getting their walls removed, and you need a happy cell if you want to watch a process that’s not totally dominated by stress response. It turns out that there are [cytokinins in coconut water](https://www.science.org/doi/10.1126/science.94.2441.350) helpful to protoplast regeneration. We don’t know all their identities or how they work, but harsh processing of the water makes them not work. So there I was, brand new scientist in Whole Foods buying a coconut. For Science.

During my PhD, I did many procedures that can now be automated at scale - cloning many genes, transforming bacteria, protein expression and blotting.

I also did confocal microscopy on plants, high pressure freezing and cryoEM, used ionic liquids, transformed and crossed Arabidopsis, used a fluorimeter to profile fabric dyes, cracked a coconut, and many bespoke things I have forgotten.

I think this experience is quite typical, especially for scientists who work with plant, animal, or fungi systems - systems which aren’t fully amenable to liquid handling. There is a stupendous long tail of procedures that are necessary, require a high level of care and expertise, which are not done at vast scale, and which are particularly difficult for robotics to automate.

I did my PhD in the early days of lab automation, but if you could fully automate my cloning work and synthesize all my genes, I’d have just shifted the time onto the confocal microscope and thought nothing different of it.

## Lab Automation is Highly Successful for Certain Tasks

Lab automation is hugely successful and valuable because it targets assays that need to operate at enormous scale to realize their full potential.

When an assay reaches a certain scale, the scale itself becomes the overriding challenge, especially to minimize drift in the assay between operators and between the first and millionth run. These cases are the extreme demonstration of the principle: “Give me six hours to chop down a tree and I will spend the first four sharpening the axe”.

The best way to do the task in both quality and price is to build a system to automate it. The life sciences manifestation of the [XKCD automation chart](https://xkcd.com/1205/).

I love lab automation. I used to take a video of robotic liquid handlers at every ASHG conference where I saw them. The leaders in the space are contributing huge value to help scientists work at scale. In part, this is because they are smart about how they run their services, focusing on the assays that make the most sense to scale and automate.

So how will the concept of AI lab-in-loop interact with this? I think AI lab-in-loop is a great idea. There will be all sorts of challenges in implementing it, but the upsides are clear.

Some of those upsides: to use general knowledge to bootstrap new procedures. To rapidly optimize protocols by intelligent exploration of the protocol space and be able to incorporate that date in a nuanced way to inform the next set of experiments, and to reduce the gating on manual human steps in development of new assays.

It may come up with new assays not previously considered, but which are either cheap/trivial extensions of ones already developed, or fully new protocols.

But these are changes in the quantity of output, not in the qualitative nature of the target tasks. AI lab-in-loop will help lab automation move faster, and by shifting the cost part of the cost-benefit bar to automation. It will help as automation methodically, protocol-by-protocol progresses through the extremely long list of protocols, rank ordered by automation value.

All things being equal, this increasing automation will just shift human work more toward the remaining bottlenecks in doing science.

However, there is one trend which I feel is more important and has been occurring for longer than the large application of lab robots. And I feel obligated to discuss it.

## Long-Tail Lab Work Faces More Fundamental Pressure from “Resource Contention”

Over the years, I feel it is getting somewhat harder to resource the sort of projects that most heavily use long-tail work.

In both industry and academia, it is a bit easier to allocate resources to projects where scale is a justification in-itself for the project, and harder to defend projects where the outputs are smaller or less interconnected with grand projects.

It is not that the different types of projects (scale-centric versus long-tail centric) compete with each other in terms of what they do. It is instead that there are limited resources to allocate across all projects. I call this “Resource Contention”.

Another explanation that makes this distinct to me is that two enzymes may not compete with each other for their substrate, but they may be limited by ATP availability or carbon partitioning, and so may indirectly limit each other.

In an environment where resources are plentiful, this might not matter. But this environment is pretty resource constrained, especially in biotech which has felt a serious pinch since 2022.

In industry, some of this is driven by the fact that scaled assays generate a large data resource that is very easy to communicate to executive leadership or investors as a defensible data asset. Similarly, in academia, or grant-driven processes it’s a lot easier to explain the output of a funding initiative if it will produce a big data resource.

I mostly want to observe this trend, not necessarily to criticize it. Those big data resources are indeed extremely valuable. When they can be made openly available to the broad research community, they can serve as the foundation that nucleates a huge array of long-tail work by giving a pre-processed foundation of the core.

But long tail-centric work is also of unique value. I am drawn to cases where a dedicated researcher worked in an area to show its potential. In the last few years, I read *The Code Breaker* about the discovery and development of CRISPR and *Breaking Through: My Life in Science* by Katalin Karikó who developed foundational research for mRNA vaccines. I strongly recommend both books; they are compelling stories which communicate the importance of supporting a wide array of research projects.

Lab automation and AI lab-in-loop may then have an indirect effect, because it will make at-scale projects more compelling, or improve their return. But this will be more similar to the way I perceive software engineering looks, where the decision to buy a GPU cluster contends for resources with personnel, even though they are complements, not substitutes with each other in terms of output for a task.

## Final Thoughts

Predictions that an AI system can’t do something have a quite poor track record. So this prediction isn’t about capability, it’s about ordering. My final words are - there’s a lot of valuable low hanging fruit, and for the present time humans still have plenty of tough nuts to crack.


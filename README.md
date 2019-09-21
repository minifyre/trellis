# Trellis

***Note**: this is an experimental project that may be abandoned if it does not show promise or develop into something with clear, tangible benefits.*

A minimal "monorepo" to centralize devDependencies &amp; the build pipeline of related repos (goal of version 1.0).

## Why Trellis?

Trellis aims to follow the 80/20 rule & capture as many of the benefits of monorepos without incurring extra costs/complexities associated with them.

Which helps prevent projects from morphing into unmaintainable, multi-headed beasts (jk, [Lerna](https://github.com/lerna/lerna) is great in certain contexts).

Trellis is mainly designed for projects of smaller scope where larger toolsets, like the aforementioned [Lerna](https://github.com/lerna/lerna), would be overkill.

## What is Trellis?

Trellis is (currently) a glorified parent folder to put repos in that share the same devDependencies (to reduce redundancy) & build pipeline.

If breaking changes are introduced in the pipeline or devDependencies, then an updated version of Trellis can be temporarily installed parallel to the original installation until all repos can be tested & successfully migrated to the new version.

*Tooling will be developed/improved to help automate the testing & transition process.*

## How can I use Trellis?

## Why Call it Trellis?

> Trellis- *noun* a framework of light wooden or metal bars, chiefly used as a support for fruit trees or climbing plants.

Just as a physical trellis serves to support similar types of growing plants, so to does this project aim to provide a consistent, centrally updatable structure to projects with similar dependencies (the build pipeline is to the physical structure as dependencies are to the soil).

Trellis is also based upon the understanding that everything dies.

> There's nothing in nature that grows indefinitely except cancer —Ricardo Semler

As such, it is only natural that when breaking changes are introduced, a new version of trellis is installed next to the original, until the old repos can be transferred to the new environment.

And coding, just like gardening, takes discipline to ensure that things don't grow out of hand with an ever-growing number of versioned silos.

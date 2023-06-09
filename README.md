![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg)

![Chip overview](https://github.com/aiunderstand/tt03p5-4-trit-balanced-ternary-counter-bt_signb_bt-radix-convertor/blob/main/overview.png)


![Vivado simulation results](https://github.com/aiunderstand/tt03p5-4-trit-balanced-ternary-counter-bt_signb_bt-radix-convertor/blob/main/vivado_simulation_result.png)

![Counter design](https://github.com/aiunderstand/tt03p5-4-trit-balanced-ternary-counter-bt_signb_bt-radix-convertor/blob/main/counter_design.png)

![FPGA test](https://github.com/aiunderstand/tt03p5-4-trit-balanced-ternary-counter-bt_signb_bt-radix-convertor/blob/main/basys3_fpga.jpg)

> Note: this is an experimental template for Tiny Tapeout 03p5 (3.5). Please talk to us before using it!

# What is Tiny Tapeout?

TinyTapeout is an educational project that aims to make it easier and cheaper than ever to get your digital designs manufactured on a real chip!

Go to https://tinytapeout.com for instructions!

## How to change the Wokwi project

Edit the [info.yaml](info.yaml) and change the wokwi_id to match your project.


## How to enable the GitHub actions to build the ASIC files

Please see the instructions for:

* [Enabling GitHub Actions](https://tinytapeout.com/faq/#when-i-commit-my-change-the-gds-action-isnt-running)
* [Enabling GitHub Pages](https://tinytapeout.com/faq/#my-github-action-is-failing-on-the-pages-part)

## How does it work?

When you edit the info.yaml to choose a different ID, the [GitHub Action](.github/workflows/gds.yaml) will fetch the digital netlist of your design from Wokwi.

After that, the action uses the open source ASIC tool called [OpenLane](https://www.zerotoasiccourse.com/terminology/openlane/) to build the files needed to fabricate an ASIC.

## Resources

* [FAQ](https://tinytapeout.com/faq/)
* [Digital design lessons](https://tinytapeout.com/digital_design/)
* [Learn how semiconductors work](https://tinytapeout.com/siliwiz/)
* [Join the community](https://discord.gg/rPK2nSjxy8)

## What next?

* Share your GDS on Twitter, tag it [#tinytapeout](https://twitter.com/hashtag/tinytapeout?src=hashtag_click) and [link me](https://twitter.com/matthewvenn)!

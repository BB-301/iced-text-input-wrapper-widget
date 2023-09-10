# Iced Text Field Wrapper Widget

This is a simple project containing an example of a custom [Iced widget](https://github.com/iced-rs/iced/blob/0.10/core/src/widget.rs) that wraps the official [TextInput](https://github.com/iced-rs/iced/blob/0.10/widget/src/text_input.rs) widget and lets the user subscribe to messages about the latter's **focused state** changes.

The idea for the project came to me while reading [this question](https://discord.com/channels/628993209984614400/1150093449303969952) on Iced's [Discord server](https://discord.gg/3xZJ65GAhd), where the OP was asking whether it was possible to get notified when an input was **blurred**. I thought that it was an interesting question, so I started looking for a solution and found nothing.

## Warning

I am just starting out with Iced and I still have a lot to learn, so it is possible that my implementation of the [Widget](https://github.com/iced-rs/iced/blob/0.10/core/src/widget.rs) trait is not optimal, so please use this example with care and seek further advice if you are in doubt. And please feel free to let me know if you find anything wrong with my implementation!
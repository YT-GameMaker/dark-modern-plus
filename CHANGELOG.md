# Change Log

All notable changes to the "dark-modern-plus" extension will be documented in this file.

## [4.0.8] - 2026-05-19

- Rebalance bracket pair highlight sequencing so the alternating blue and pink levels line up consistently across nested pairs.
- Change C# delegate coloring to use the type color instead of the method color in both semantic and fallback token rules.
- Set the fallback `entity.name.function.cs` color to the default foreground to reduce misleading method-name highlighting before semantic tokens arrive.

## [4.0.7] - 2026-4-27

- Unify overloaded operator color with built-in operators (both now use the default foreground color).

## [4.0.6] - 2026-4-27

- Fix selection highlight disappearing when right-clicking: restore a visible `editor.inactiveSelectionBackground` instead of transparent.

## [4.0.0] - 2026-4-27

- Recalibrate all token colors using a perceptually uniform color space for more consistent brightness and saturation.
- Extend C# coloring conventions to other common languages: HTML, CSS, JavaScript, Markdown, JSON, XML, and regular expressions now follow the same semantic color roles.
- Add per-language bracket pair colors aligned with the C# bracket color scheme.
- Improve popup and menu background colors, selection backgrounds, and word-highlight styling.

## [3.0.1] - 2026-4-24

- Refine C# preprocessor directive colors so directive keywords align with control-flow styling and directive text stays visually stable.

## [3.0.0] - 2026-4-23

- Rework the C# semantic and fallback token colors while keeping the Dark Modern base style.
- Fine-tune comments, XML doc comments, namespaces, locals, generic type parameters, and method parameters.
- Rebalance bracket colors and improve separation between selected text, same-symbol highlights, and find-match highlights.
- Adjust the editor background and related interaction colors for more consistent contrast.

# swift-theme

Use this package when you need to name a light or dark theme, or hold one value for the light theme and one for the dark theme. Start from `Theme`, which has the cases `light` and `dark`, and use `Theme.Product<Value>` for the pair of values.

## Laws

- `Theme.allCases` and `Theme.Product.values` list light before dark.

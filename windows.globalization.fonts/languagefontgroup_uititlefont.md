---
-api-id: P:Windows.Globalization.Fonts.LanguageFontGroup.UITitleFont
-api-type: winrt property
---

<!-- Property syntax
public Windows.Globalization.Fonts.LanguageFont UITitleFont { get; }
-->

# Windows.Globalization.Fonts.LanguageFontGroup.UITitleFont

## -description
Gets a font that is recommended for special UI elements set at sizes much larger than typical UI body text.

## -property-value
The recommended [LanguageFont](languagefont.md).

## -remarks
The [UITitleFont](languagefontgroup_uititlefont.md) property provides a font recommendation for special UI elements set at sizes much larger than typical UI body text—typically 36 pt. or above.

The font recommended for this usage case may be differentiated from other UI usage cases in font weight, style or stretch values. Those attributes are significant aspects of the font recommendation being provided.

A [UITitleFont](languagefontgroup_uititlefont.md) recommendation is available for every supported language or script.

## -examples

## -see-also
[Guidelines and checklist for text and typography](http://msdn.microsoft.com/library/1b8b90ad-cdc4-4997-acde-871c1e94a929), [Understanding the Windows 8 silhouette](http://msdn.microsoft.com/library/2d4ec23b-185e-4f44-a302-02b77b0d4cee)
# ITY-Accessibility-Toolbar

1. unpkg
Unpkg automatically serves npm packages.
If your package name is ity-accessibility-toolbar, the latest version is:

<script src="https://unpkg.com/ity-accessibility-toolbar"></script>


If you want a specific version:

<script src="https://unpkg.com/ity-accessibility-toolbar@1.0.0"></script>

......................................

2. jsDelivr
Same idea, but a different CDN:

<script src="https://cdn.jsdelivr.net/npm/ity-accessibility-toolbar"></script>


Specific version:

<script src="https://cdn.jsdelivr.net/npm/ity-accessibility-toolbar@1.0.0"></script>

......................................

3. How to use
Once you load the script in any HTML page, your toolbar will appear automatically (based on your IIFE code).
Example:

<!DOCTYPE html>
<html>
<head>
    <title>Test Accessibility Toolbar</title>
</head>
<body>
    <p>Select some text and click the Listen button.</p>

    <script src="https://unpkg.com/ity-accessibility-toolbar"></script>
</body>
</html>



If you want options (like background color, position, etc.), we’ll need to add a configuration object to your script so people can call:

ITYAccessibilityToolbar.init({
  listenLabel: "🔉 Speak Now",
  stopLabel: "🛑 Stop",
  increaseFontLabel: "Increase A",
  decreaseFontLabel: "Decrease A",
  contrastLabel: "Toggle Contrast",
  fontStep: 2,
  position: { bottom: "30px", right: "30px" }
});



=======================

If you click on contrast, then "high-contrast" class will be add on body tag and based on that you can write your own css for your elements.

If you have any question, you can provide comment/issue regarding this plugin.



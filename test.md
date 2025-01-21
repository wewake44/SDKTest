# webapp
## The package manifest

An app can provide own menu entries, use the reverse proxy infrastructure including permissions and the storage solution. This document describes the different integration points and how they work.

The package-manifest is essential for the integration points. Beside the snapcraft.yaml, it is strongly recommended that the app has to provide the package manifest to be integrated into the ctrlX CORE system. The package-manifest file should follow the naming structure `<app name>.<package-manifest>.json` where `<app name>` and the `id` property in the package-manifest are both set to the `name (technical app name)` as mentioned in the [snapcraft](appdevguide_basechecks.md) documentation.

The package-manifest file name should follow the pattern:

    <snap name>.package-manifest.json

The _snap name_ is the _name_ of your app, configured by the _snapcraft.yaml_.


The package-manifest file name should follow the pattern:

    <snap name>.package-manifest.json

The _snap name_ is the _name_ of your app, configured by the _snapcraft.yaml_.

```html
<div style="border: 1px solid #ccc; padding: 10px; border-radius: 5px;">
  <textarea id="userInput" style="width: 100%; height: 100px;"></textarea>
</div>

<button onclick="displayUserInput()">Display Input</button>

<p>User Input: <span id="displayUserInput"></span></p>

<script>
  function displayUserInput() {
    const userInputValue = document.getElementById('userInput').value;
    document.getElementById('displayUserInput').innerText = userInputValue;
  }
</script>

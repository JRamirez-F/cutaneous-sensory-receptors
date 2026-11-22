# Cutaneous Sensory Receptors

Interactive physiology simulator of cutaneous **mechanoreception** and **thermoreception**. Includes **Explore** and **Prediction Mode**, synchronized electrophysiological recordings, interactive SVG anatomy, a scientific bibliography, and **English / Spanish** support. English is the default language.

**Credits:** Created by Jorge Ramírez Franco and ChatGPT (OpenAI). Department of Physiology · Complutense University of Madrid.

## Run locally

Open `index.html` in a modern browser (Chrome, Edge, Safari, or Firefox). The application is self-contained and does not require an Internet connection for its core functionality. Links to scientific references and licenses need an Internet connection to open.

## Host with GitHub Pages

Copy `index.html` and `LICENSE.md` into the desired subfolder of the repository serving your GitHub Pages website, for example `sensory-receptors/`. Then link to that folder from your website's navigation. GitHub Pages will serve `index.html` automatically when the directory is visited, provided Pages is configured for that repository/path.

The simulator does not require npm, a build tool, or a back-end server.

## Using the simulator

Select **Mechanoreception** or **Thermoreception**. In **Explore**, the receptor identities and their corresponding anatomical diagrams are visible. In **Prediction Mode**, use stimulus responses to identify anonymous units and check your answers. Drag recordings horizontally to pan; use +/− to zoom.

Select **ES** for Spanish (Spain). Switching languages does not reset the recordings.

## Scientific limitations

The models are intended for education, not to reproduce calibrated human recordings. Relative pressure, vibration and temperature-response parameters are illustrative. TRP channel annotations do not mean each human thermal afferent maps to exactly one molecular channel. Human SA II anatomical correspondence remains uncertain.

## Licenses

**Noncommercial only.** The code is covered by **PolyForm Noncommercial 1.0.0**, while original educational content and original illustrations are covered by **CC BY-NC 4.0**, subject to the rights and limitations described in [LICENSE.md](LICENSE.md). Neither license grants commercial reuse.

Before publishing, verify rights/attribution for the supplied free-nerve-ending SVG template used in the thermal illustration. Cited papers and institutional identifiers retain their respective owners' rights.

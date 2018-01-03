# Metal Test

See the demo here:

## Setup

No install or build needed, just download and enjoy! 

## Frameworks and Libraries 

Vue was used for the dropdown menu. I used plain CSS (flexbox for responsiveness) because Bootstrap would be overkill/not ideal for precise spacing. Lottie was used for the animation, but since the CDN had some issues, I simply used the import in demo.html.

## Note on the animation

iFrame is definitely not an ideal solution, but in the interests of getting a visually complete prototype in time, this was a quick fix as opposed to pasting the demo code or importing it (which wasn't CORS compliant here). With a system such as Webpack and a framework such as Vue, it would be fine to divide huge files and build them together, or to dive into Lottie's docs to learn more about how it works.
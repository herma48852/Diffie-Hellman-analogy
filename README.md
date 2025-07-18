# Diffie-Hellman Shared Secret Analogy

This project provides an interactive HTML presentation that explains the Diffie-Hellman key exchange protocol using a simple and intuitive paint-mixing analogy. It illustrates how two parties can establish a shared secret over an insecure channel, even in the presence of an eavesdropper.

## Table of Contents

* [About the Project](https://www.google.com/search?q=%23about-the-project)

* [How it Works](https://www.google.com/search?q=%23how-it-works)

* [Technologies Used](https://www.google.com/search?q=%23technologies-used)

* [Usage](https://www.google.com/search?q=%23usage)

* [Credits](https://www.google.com/search?q=%23credits)

## About the Project

The `main.html` file is a single-page web presentation designed to demystify the Diffie-Hellman key exchange. It breaks down the complex cryptographic concept into easy-to-understand steps using a visual analogy of mixing paint colors. Each "slide" (section) progressively builds upon the previous one, explaining the roles of public and private information in creating a shared secret that an eavesdropper cannot easily deduce.

## How it Works

The analogy proceeds through the following steps:

1. **Agree on a Common Public Color (Public Base):** Alice and Bob (and Eve, the eavesdropper) publicly agree on a starting paint color.

2. **Each Picks a Secret Personal Color (Secret Ingredient):** Alice and Bob each secretly choose their own private color. These colors are never revealed.

3. **Mix and Share a "Public Mixture":** Alice mixes her secret color with the public base color, and Bob does the same with his secret color. They then publicly exchange these newly mixed colors. Eve sees these mixed colors, but not the original secret colors or their exact ratios.

4. **What Eve Sees (and Doesn't See):** This section highlights that while Eve observes all public exchanges, she lacks the crucial private information (Alice's and Bob's secret colors) to recreate the final secret. The concept of "unmixing" being impossible is emphasized.

5. **Creating the Shared Secret (Final Secret Mix):** Alice takes Bob's public mixture and adds her *original secret color* to it. Similarly, Bob takes Alice's public mixture and adds his *original secret color*. Due to the mathematical properties of the Diffie-Hellman exchange (represented by the paint mixing), they both arrive at the exact same unique final color.

6. **The Shared Secret: Our Invisible Ink Formula:** The final, shared color is presented as their "invisible ink formula," which can be used for secure communication.

7. **Recap: The Secret Sharing Journey:** A summary of all the steps involved in establishing the shared secret.

## Technologies Used

* **HTML5:** For structuring the content.

* **Tailwind CSS:** A utility-first CSS framework used for styling and responsive design.

* **Google Fonts (Inter):** For modern and legible typography.

## Usage

To view the presentation:

1. Download or clone the project.

2. Open the `main.html` file in your preferred web browser (e.g., Chrome, Firefox, Edge).

The presentation is designed to be viewed by scrolling through the sections.

## Credits

This project is an analogy for the [Diffie-Hellman Key Exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange), a foundational concept in public-key cryptography.

# Digital Image Processing

This repository contains a collection of notebooks and scripts to explore different techniques in digital image processing. The techniques covered include image equalization, noise operations, edge detection, and more.

## Contents

### Notebooks

1. **ImageEqualize.ipynb**
   - Image equalization methods.
   - Implementation of contrast stretching and histogram equalization.

2. **ImageOperation.ipynb**
   - Basic image operations, such as image multiplication and division.
   - Normalization of results for visualization.

3. **FixNoise.ipynb**
   - Noise models for images.
   - Implementation of uniform, Gaussian, and salt-and-pepper noise.

4. **BorderDetection.ipynb**
   - Introduction to edge detection in images.
   - 4-neighborhood and 8-neighborhood verification for object detection.

### Main Functions

- **salt_and_pepper_noise**: Adds salt and pepper noise to an image.
- **uniform_noise**: Adds uniform noise to an image.
- **gaussian_noise**: Adds Gaussian noise to an image.
- **verifica4neighborhood**: Verifies objects using 4-neighborhood.
- **verifica8neighborhood**: Verifies objects using 8-neighborhood.

## Requirements

- Python 3.6 or higher
- Libraries: `numpy`, `matplotlib`, `opencv-python`

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks using Jupyter:
   ```bash
   jupyter notebook
   ```

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

# Raster Tile

A project for creating raster tiles from geospatial data.

## Features
- Generate raster tiles from various geospatial data sources.
- Supports different map projections and coordinate systems.
- Customizable tile size and resolution.

## Prerequisites
- Python 3.6+
- Required libraries: GDAL, NumPy, Matplotlib

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/SreelekshmiKS1994/raster-tile.git
   ```
2. Navigate to the project directory:
   ```sh
   cd raster-tile
   ```
3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your geospatial data.
2. Run the tile generation script:
   ```sh
   python generate_tiles.py --input <input_file> --output <output_directory> --tile-size <size> --projection <projection>
   ```
3. Customize the parameters as needed.

## Examples
```sh
python generate_tiles.py --input data/map.tif --output tiles/ --tile-size 256 --projection EPSG:3857
```

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.

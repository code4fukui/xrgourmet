# xrgourmet - XRグルメ

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An open-data collection of 3D-scanned food models for use in AR and VR applications.
(AR表示したりVRで使うためのグルメ系3Dモデルオープンデータを集めます)

## XR Gourmet Gallery

Explore the full collection of 3D food models in your browser.

**[View the Live Demo](https://code4fukui.github.io/xrgourmet/)**

The gallery provides multiple ways to view each model:
*   **AR (Augmented Reality):** On compatible devices (like iPhone or iPad), clicking a model's image will open it directly in AR.
*   **VR/3D Viewer:** On other devices, a web-based 3D/VR viewer will launch, built with technologies like A-Frame and Three.js.
*   **Direct Downloads:** Links are provided to download the raw `.glb` and `.usdz` model files.


![A gallery view of various 3D-scanned food items, including steak, takoyaki, curry, and parfait.](https://code4fukui.github.io/xrgourmet/mutsunohana-steak.jpg)


## Featured Models

Here are a few examples from the collection. Each entry includes the dish, the restaurant/source, and links to view or download the model.

| Dish Preview | Name | Source | Links |
| :--- | :--- | :--- | :--- |
| <img src="https://code4fukui.github.io/xrgourmet/lejardin-waton.jpg" width="150"> | Waton Pork Dish (和豚料理) | [Le Jardin](https://lejardin-fukui.com/) | [APP](https://code4fukui.github.io/xrgourmet/lejardin-waton.html) / [USDZ](https://code4fukui.github.io/xrgourmet/lejardin-waton.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/lejardin-waton.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/takoyaki-takobei.jpg" width="150"> | Takoyaki (たこ焼き) | [Takobei (蛸べえ)](https://www.hotpepper.jp/strJ000985159/) | [APP](https://code4fukui.github.io/xrgourmet/takoyaki-takobei.html) / [USDZ](https://code4fukui.github.io/xrgourmet/takoyaki-takobei.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/takoyaki-takobei.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/kosen-dago.jpg" width="150"> | Kosen Dago (高専ダゴ) | [Kosen Dago](http://www.kousendago.com/) | [APP](https://code4fukui.github.io/xrgourmet/kosen-dago.html) / [USDZ](https://code4fukui.github.io/xrgourmet/kosen-dago.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/kosen-dago.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.jpg" width="150"> | Strawberry Tiramisu Parfait | [Sweets Bar Salice](https://www.instagram.com/salicefukui_pr/) | [APP](https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.html) / [USDZ](https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/echizen-seikogani.jpg" width="150"> | Echizen Seiko Crab (越前せいこがに) | (N/A) | [APP](https://code4fukui.github.io/xrgourmet/echizen-seikogani.html) / [USDZ](https://code4fukui.github.io/xrgourmet/echizen-seikogani.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/echizen-seikogani.glb) |

## Usage

### For Viewing
Simply visit the [XR Gourmet Gallery](https://code4fukui.github.io/xrgourmet/) to browse and interact with the models on your desktop or mobile device.

### For Developers
Clone this repository or download the `.usdz` and `.glb` files for use in your own 3D, AR, or VR projects. The HTML files serve as simple examples of how to display these models on the web.

## Contributing

Contributions are welcome! If you have a 3D-scanned food model you'd like to add:
1.  Fork the repository.
2.  Add your `.glb`, `.usdz`, and a preview `.jpg` file.
3.  Create an HTML viewer page (you can use an existing one as a template).
4.  Add your model to the list in `index.html`.
5.  Submit a pull request with your changes.

## License

The data is available under the [CC BY](https://creativecommons.org/licenses/by/4.0/) license. Please attribute to [Code for FUKUI](https://github.com/code4fukui/xrgourmet).
# segmentation of cells and cell nuclei on medical images

The main method for diagnosing cervical cancer at any stage of the disease is taking a gynecological smear followed by a PAP-test, upon which diagnosis is established based on pronounced changes in the structure and composition of the cells in the smear. Thus, an urgent task is to develop a decision support system for gynecologists, which makes it possible to automatically highlight the most striking signs of the disease in order to speed up the diagnostic process. One of the requirements for such a system is the correct segmentation of cells and cell nuclei, which allows further algorithmization of pathology detection on a microscopic image of a smear.

Microscopic image of cell structures after a PAP-test: 
![photo-emotion](https://github.com/whyclos/nuclei-segmentation-neural-nw/raw/main/images/macro.png)
Segmentation is carried out based on the color of the cells, the number of nuclei or their absence. Cell size and the cytoplasm-nucleus ratio also matter. Based on the ratio of cells of different colors diagnosis is established.

Full-size image is difficult to process 

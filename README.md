# Qt ZipViewer
A simple archives viewer that uses minizip 2 library and written with Model-View architecture.

To clone entire project with submodules use:  
`git clone --recurse-submodules https://github.com/vaedermakar/Qt_ZipViewer`

Or `git submodule init` + `git submodule update` after default cloning.

![Image alt](https://github.com/vaedermakar/Qt_ZipViewer/raw/main/src/screenshots/screenshot.png)  

---
 ### Current problems/bugs/imperfections:  
- on Linux, when using the Plasma desktop environment, the QFileDialog object may not send the urlSelected() signal, which means that you will have to enter the path to the file manually;

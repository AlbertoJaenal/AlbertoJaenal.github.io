---
layout: page
title: Publications
permalink: /publications/
---

<style>
.view-toggle {
  margin: 20px 0;
  text-align: center;
}

.view-toggle button {
  padding: 10px 20px;
  margin: 0 10px;
  background-color: #f0f0f0;
  border: 2px solid #ddd;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
  transition: all 0.3s;
}

.view-toggle button:hover {
  background-color: #e0e0e0;
}

.view-toggle button.active {
  background-color: #2a7ae2;
  color: white;
  border-color: #2a7ae2;
}

.view-content {
  display: none;
}

.view-content.active {
  display: block;
}

.publication-item {
  margin-bottom: 20px;
  padding-bottom: 15px;
  border-bottom: 1px solid #eee;
}

.publication-item:last-child {
  border-bottom: none;
}

.publication-title {
  font-weight: bold;
  color: #2a7ae2;
  margin-bottom: 5px;
}

.publication-authors {
  color: #666;
  margin-bottom: 3px;
}

.publication-venue {
  font-style: italic;
  margin-bottom: 5px;
}

.publication-links a {
  margin-right: 10px;
  color: #2a7ae2;
}
</style>

<div class="view-toggle">
  <button id="btn-by-year" class="active" onclick="showView('by-year')">View by Year</button>
  <button id="btn-by-type" onclick="showView('by-type')">View by Type</button>
</div>

<script>
function showView(view) {
  // Hide all views
  document.querySelectorAll('.view-content').forEach(el => {
    el.classList.remove('active');
  });
  
  // Deactivate all buttons
  document.querySelectorAll('.view-toggle button').forEach(btn => {
    btn.classList.remove('active');
  });
  
  // Show selected view and activate button
  document.getElementById('view-' + view).classList.add('active');
  document.getElementById('btn-' + view).classList.add('active');
}
</script>

<!-- View by Year -->
<div id="view-by-year" class="view-content active" markdown="1">

### 2025

**Towards Visual Localization Interoperability: Cross-Feature for Collaborative Visual Localization and Mapping**  
A. Jaenal, P. C. Cubero, J. Araujo, A. Mateus  
*2025 IEEE/CVF International Conference on Computer Vision (ICCV)*, pp. 26783-26792
[DOI](https://doi.org/10.1109/ICCV51701.2025.02486)

**ColabSfM: Collaborative Structure-from-Motion by Point Cloud Registration**  
J. Edstedt, A. Jaenal, A. Mateus  
*2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, pp. 6573-6583
[DOI](https://doi.org/10.1109/CVPR52734.2025.00616)

**Cross-Detector Visual Localization with Coplanarity Constraints for Indoor Environments**  
J.L. Matez-Bandera, A. Jaenal, C. Gomez, A. C. Hernandez, J. Monroy, J. Araujo, J. Gonzalez-Jimenez  
*MDPI Sensors*, 2025
[DOI](https://doi.org/10.3390/s25247593)

### 2024

**Leveraging scale-and orientation-covariant features for planar motion estimation**  
M. V. Örnhag, A. Jaenal  
*European Conference on Computer Vision*, 2024, pp. 418-434
[DOI](https://doi.org/10.1007/978-3-031-72949-2_24)

**MachNet, a general Deep Learning architecture for Predictive Maintenance within the industry 4.0 paradigm**  
A. Jaenal, J.R. Ruiz-Sarmiento, J. Gonzalez-Jimenez  
*Engineering Applications of Artificial Intelligence*, vol. 127, pp. 107365, 2024 (Q1, T1)
[DOI](https://doi.org/10.1016/j.engappai.2023.107365)

### 2023

**Sequential Monte Carlo localization in topometric appearance maps**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*The International Journal of Robotics Research*, 2023 (Q1, T1)
[DOI](https://doi.org/10.1177/02783649231197723)

**Appearance-based Localization**  
Alberto Jaenal, Francisco-Angel Moreno, Javier Gonzalez-Jimenez  
*University of Málaga*, 2023
[Link](https://hdl.handle.net/10630/30592)

### 2022

**Robot@VirtualHome, an ecosystem of virtual environments and tools for realistic indoor robotic simulation**  
D. Fernandez-Chaves, J.R. Ruiz-Sarmiento, A. Jaenal, N. Petkov, J. Gonzalez-Jimenez  
*Expert Systems with Applications*, vol. 208, pp. 117970, 2022 (Q1, T1)
[DOI](https://doi.org/10.1016/j.eswa.2022.117970)

**Unsupervised Appearance Map Abstraction for Indoor Visual Place Recognition With Mobile Robots**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*IEEE Robotics and Automation Letters*, vol. 7, no. 3, pp. 8495-8501, 2022
[DOI](https://doi.org/10.1109/LRA.2022.3186768)

**Dimensionality Reduction in images for Appearance-based camera Localization**  
S. Luengo, A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*XLIII Jornadas de Automática*, Logroño, Spain, 2022
[DOI](https://doi.org/10.17979/spudc.9788497498418)

### 2021

**Appearance-Based Sequential Robot Localization Using a Patchwise Approximation of a Descriptor Manifold**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*MDPI Sensors*, vol. 21, no. 7, pp. 2483, 2021 (Q1, T1)
[DOI](https://doi.org/10.3390/s21072483)

**Experimental Analysis of Appearance Maps as Descriptor Manifolds Approximations**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*Computer Analysis of Images and Patterns*, pp. 109-119, 2021
[DOI](https://doi.org/10.1007/978-3-030-89131-2_10)

### 2020

**The UMA-VI dataset: Visual–inertial odometry in low-textured and dynamic illumination environments**  
D. Zuniga-Noel, A. Jaenal, R. Gomez-Ojeda, J. Gonzalez-Jimenez  
*The International Journal of Robotics Research*, 2020
[DOI](https://doi.org/10.1177/0278364920938439)

**Improving Visual SLAM in Car-Navigated Urban Environments with Appearance Maps**  
A. Jaenal, D. Zuniga-Noel, R. Gomez-Ojeda, J. Gonzalez-Jimenez  
*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, pp. 4679-4685, 2020
[DOI](https://doi.org/10.1109/IROS45743.2020.9341451)


### 2019

**Urban Monitoring of Unpleasant Odors with a Handheld Electronic Nose**  
A. Gongora, A. Jaenal, D. Fernandez-Chaves, J. Monroy, J. Gonzalez-Jimenez  
*ISOCS/IEEE International Symposium on Olfaction and Electronic Nose (ISOEN)*, Fukuoka, Japan, 2019
[DOI](http://dx.doi.org/10.1109/ISOEN.2019.8823219)

**Experimental Study of the Suitability of CNN-based Holistic Descriptors for Accurate Visual Localization**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*Proceedings of the 2nd International Conference on Applications of Intelligent Systems (APPIS '19)*, Las Palmas de Gran Canaria, Spain, pp. 28:1-28:6, 2019
[DOI](http://dx.doi.org/10.1145/3309772.3309800)

### 2018

**Toward the Generation of Smell Maps: Matching Electro-Chemical Sensor Information with Human Odor Perception**  
A. Gongora, D. Fernandez-Chaves, A. Jaenal, J. Monroy, J. Gonzalez-Jimenez  
*International Conference on Applications of Intelligent Systems (APPIS)*, Las Palmas de Gran Canaria, Spain, 2018

**Toward the Generation of Smell Maps: Matching Electro-Chemical Sensor Information with Human Odor Perception**  
A. Gongora, D. Fernandez-Chaves, A. Jaenal, J. Monroy, J. Gonzalez-Jimenez  
*Frontiers in Artificial Intelligence and Applications (FAIA)*, IOS Press, pp. 134-145, 2018
[DOI](http://dx.doi.org/10.3233/978-1-61499-929-4-134)



</div>

<!-- View by Type -->
<div id="view-by-type" class="view-content" markdown="1">

## Journal Publications (7)

**Cross-Detector Visual Localization with Coplanarity Constraints for Indoor Environments**  
J.L. Matez-Bandera, A. Jaenal, C. Gomez, A. C. Hernandez, J. Monroy, J. Araujo, J. Gonzalez-Jimenez
*MDPI Sensors*, 2025  
[DOI](https://doi.org/10.3390/s25247593)

**MachNet, a general Deep Learning architecture for Predictive Maintenance within the industry 4.0 paradigm**  
A. Jaenal, J.R. Ruiz-Sarmiento, J. Gonzalez-Jimenez  
*Engineering Applications of Artificial Intelligence*, vol. 127, pp. 107365, 2024 (Q1, T1)
[DOI](https://doi.org/10.1016/j.engappai.2023.107365)

**Sequential Monte Carlo localization in topometric appearance maps**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*The International Journal of Robotics Research*, 2023 (Q1, T1)
[DOI](https://doi.org/10.1177/02783649231197723)

**Robot@VirtualHome, an ecosystem of virtual environments and tools for realistic indoor robotic simulation**  
D. Fernandez-Chaves, J.R. Ruiz-Sarmiento, A. Jaenal, N. Petkov, J. Gonzalez-Jimenez  
*Expert Systems with Applications*, vol. 208, pp. 117970, 2022 (Q1, T1)
[DOI](https://doi.org/10.1016/j.eswa.2022.117970)

**Unsupervised Appearance Map Abstraction for Indoor Visual Place Recognition With Mobile Robots**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*IEEE Robotics and Automation Letters*, vol. 7, no. 3, pp. 8495-8501, 2022
[DOI](https://doi.org/10.1109/LRA.2022.3186768)

**Appearance-Based Sequential Robot Localization Using a Patchwise Approximation of a Descriptor Manifold**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*MDPI Sensors*, vol. 21, no. 7, pp. 2483, 2021 (Q1, T1)
[DOI](https://doi.org/10.3390/s21072483)

**The UMA-VI dataset: Visual–inertial odometry in low-textured and dynamic illumination environments**  
D. Zuniga-Noel, A. Jaenal, R. Gomez-Ojeda, J. Gonzalez-Jimenez  
*The International Journal of Robotics Research*, 2020
[DOI](https://doi.org/10.1177/0278364920938439)

---

## Conference Papers (5)

**Towards Visual Localization Interoperability: Cross-Feature for Collaborative Visual Localization and Mapping**  
A. Jaenal, P. C. Cubero, J. Araujo, A. Mateus  
*2025 IEEE/CVF International Conference on Computer Vision (ICCV)*, pp. 26783-26792
[DOI](https://doi.org/10.1109/ICCV51701.2025.02486)

**ColabSfM: Collaborative Structure-from-Motion by Point Cloud Registration**  
J. Edstedt, A. Jaenal, A. Mateus  
*2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, pp. 6573-6583
[DOI](https://doi.org/10.1109/CVPR52734.2025.00616)

**Leveraging scale-and orientation-covariant features for planar motion estimation**  
M. V. Örnhag, A. Jaenal  
*European Conference on Computer Vision*, 2024, pp. 418-434
[DOI](https://doi.org/10.1007/978-3-031-72949-2_24)

**Dimensionality Reduction in images for Appearance-based camera Localization**  
S. Luengo, A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*XLIII Jornadas de Automática*, Logroño, Spain, 2022
[DOI](https://doi.org/10.17979/spudc.9788497498418)

**Improving Visual SLAM in Car-Navigated Urban Environments with Appearance Maps**  
A. Jaenal, D. Zuniga-Noel, R. Gomez-Ojeda, J. Gonzalez-Jimenez  
*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, pp. 4679-4685, 2020
[DOI](https://doi.org/10.1109/IROS45743.2020.9341451)

**Urban Monitoring of Unpleasant Odors with a Handheld Electronic Nose**  
A. Gongora, A. Jaenal, D. Fernandez-Chaves, J. Monroy, J. Gonzalez-Jimenez  
*ISOCS/IEEE International Symposium on Olfaction and Electronic Nose (ISOEN)*, Fukuoka, Japan, 2019
[DOI](http://dx.doi.org/10.1109/ISOEN.2019.8823219)

**Experimental Study of the Suitability of CNN-based Holistic Descriptors for Accurate Visual Localization**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*Proceedings of the 2nd International Conference on Applications of Intelligent Systems (APPIS '19)*, Las Palmas de Gran Canaria, Spain, pp. 28:1-28:6, 2019
[DOI](http://dx.doi.org/10.1145/3309772.3309800)

**Toward the Generation of Smell Maps: Matching Electro-Chemical Sensor Information with Human Odor Perception**  
A. Gongora, D. Fernandez-Chaves, A. Jaenal, J. Monroy, J. Gonzalez-Jimenez  
*International Conference on Applications of Intelligent Systems (APPIS)*, Las Palmas de Gran Canaria, Spain, 2018


---

## PhD Thesis

**Appearance-based Localization**  
Alberto Jaenal, Francisco-Angel Moreno, Javier Gonzalez-Jimenez  
*University of Málaga*, 2023
[Link](https://hdl.handle.net/10630/30592)

---

## Book Chapters (2)

**Experimental Analysis of Appearance Maps as Descriptor Manifolds Approximations**  
A. Jaenal, F.A. Moreno, J. Gonzalez-Jimenez  
*Computer Analysis of Images and Patterns*, pp. 109-119, 2021
[DOI](https://doi.org/10.1007/978-3-030-89131-2_10)

**Toward the Generation of Smell Maps: Matching Electro-Chemical Sensor Information with Human Odor Perception**  
A. Gongora, D. Fernandez-Chaves, A. Jaenal, J. Monroy, J. Gonzalez-Jimenez  
*Frontiers in Artificial Intelligence and Applications (FAIA)*, IOS Press, pp. 134-145, 2018
[DOI](http://dx.doi.org/10.3233/978-1-61499-929-4-134)

</div>

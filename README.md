# ARNavigation

ARNavigation is an augmented reality application that allows users to navigate through a building's blueprint. By using AR technology, users can visualize the building layout and get directions to different parts of the structure.

## Features

- **Interactive Blueprint Navigation:** View and interact with a building's blueprint in AR.
- **Real-time Navigation:** Get real-time directions within the building.
- **Point of Interest (POI) Markers:** Highlight important locations such as exits, restrooms, and offices.
- **Scalable Models:** Works with blueprints of various sizes and complexities.

## Screenshots

![Blueprint View]![AR_1](https://github.com/user-attachments/assets/4aea7c77-de89-449c-85be-b3c7f9ce4c13)

*Interactive Blueprint View*

![Navigation Mode]![AR_2](https://github.com/user-attachments/assets/0732b2eb-d887-4e20-bdf0-4983915f4f0b)

*Navigation Mode*

## Installation

### Prerequisites

- [Unity3D](https://unity3d.com/get-unity/download) (version 2019.4 or higher)
- [Vuforia Engine](https://developer.vuforia.com/downloads/sdk) SDK

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ARNavigation.git
    cd ARNavigation
    ```

2. Open the project in Unity:
    - Launch Unity Hub.
    - Click on `Add` and select the project directory.

3. Import Vuforia Engine SDK into the project:
    - Download the Vuforia Engine SDK from the Vuforia website.
    - Import the package into Unity by going to `Assets > Import Package > Custom Package` and selecting the downloaded Vuforia package.

4. Configure Vuforia:
    - Go to `Edit > Project Settings > Player`.
    - In the `XR Settings` section, enable `Vuforia Augmented Reality`.

5. Add your Vuforia license key:
    - Go to `Window > Vuforia Configuration`.
    - Enter your Vuforia license key in the `App License Key` field.

6. Build and run the application on your preferred device.

## Usage

1. Launch the ARNavigation application on your device.
2. Point your device's camera at the blueprint of the building.
3. Interact with the AR model to navigate through the building.
4. Use the on-screen controls to get directions to different parts of the building.

## Blueprint Map
![Blueprint_Map](https://github.com/user-attachments/assets/f0775167-3e95-4d7a-a4bf-3ed566f32005)


## Technologies Used

- Unity3D
- Vuforia Engine
- C#
- Unity AR foundation

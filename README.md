# Interactive 3D Event Badge

If you find it useful, give this repository a star⭐ as a sign of thanks

## Inspiration

[Building an interactive 3D event badge with React Three Fiber](https://vercel.com/blog/building-an-interactive-3d-event-badge-with-react-three-fiber)

## The Stack

- Next Js
- Typescript
- Blender
- Three Js
- React Three Fiber
- Drei
- React-three-rapier
- MeshLine

## Installation

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Build the project

```bash
npm run build
```

### Run the project in production mode

```bash
npm run start
```

# How to Change the Front / Back Artwork of the 3D Badge

Follow these steps to update the badge texture used in the project.

## 🔧 Steps

1. Go to `public/3d/badge.glb` in your project.
2. Open **Blender**.
3. Navigate to **File → Import → glTF 2.0 (.glb/.gltf)** and select `badge.glb`.
4. Open the **Shader Editor** and click the image node to view the texture.
5. In the **Image Editor**, select **Image → Save As** and export the texture (PNG or JPG).
6. Open the exported texture in **Photoshop**, **GIMP**, or any image editor.
7. Replace the existing badge artwork with your own while keeping the same image resolution.
8. Save the edited texture.
9. Return to Blender and use **Image → Open** to re-add your updated texture.
10. Confirm that the texture displays correctly on the badge model.
11. Export the updated model via **File → Export → glTF 2.0 (.glb)**.
12. Save it **using the same filename:** `badge.glb` (so no code changes are required).
13. Replace the file at `public/3d/badge.glb` with your new version.
14. Run your project and refresh the browser to see the updated badge.


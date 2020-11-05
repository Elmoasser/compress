# compress

1. Install Node.js
1. Create new folder 
1. Open the cmd or terminal in this folder
1. type: npm init -y
1. type: npm install gltf-pipeline
1. name your model file with model.glb
1. type: npx gltf-pipeline -i model.glb -d --draco.compressionLevel 10 -o compressed.glb

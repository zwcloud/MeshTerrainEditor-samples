Brick_NormalHeight and Sand_NormalHeight is created by MTE's TextureChannelPacker tool at menu "Window/Mesh Terrain Editor/Tools/Texture Channel Packer", using mode "Normal Height".

The normal map's RGB channel becomes XXX_NormalHeight texture's RGB channel; the height maps' red channel becomes XXX_NormalHeight texture's Alpha channel. MTE's height blend shaders will sample the XXX_NormalHeight textures according to this convention.

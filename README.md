# SoftwareRasterizer
**タイトル**
CPU Software Rasterizer

**概要**
CPU上で3Dグラフィックスパイプラインを自前実装した
ソフトウェアラスタライザです。
GPUのレンダリングパイプラインをブラックボックスとして扱わず、
内部処理を理解することを目的として実装しました。

**実装項目**
・Vector3
・Matrix4x4
・Quaternion
・Transform(World)
・Camera(View)
・Projection
・Perspective Divide
・Viewport Transform
・Triangle Rasterization
・Barycentric Coordinates
・Z-Buffer
・Frame Buffer(pixelBuffer)
・Win32(GDI)表示
 
**今後の拡張予定**
・Near Plane Clipping
・Perspective Correct Interpolation
・Texture Mapping
・Lighting
・自作Rendreとの表示統合

README.md
src/
    Vector3.*
    Matrix4x4.*
    Quaternion.*
    Camera.*
    Projection.*
    Transform.*
    main.cpp

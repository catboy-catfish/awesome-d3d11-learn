# awesome-d3d
A curated list designed to aggregate some awesome resources on learning how to use the Direct3D graphics API. Mostly deals with DX11/D3D11 or DX12/D3D12.

I created this list due to not being able to easily find as much information for programming with Direct3D as I could for OpenGL or Vulkan.

I hope this helps you as much as it'll help me in the future.

# D3D 11
## Articles
- [Rodolphe Vaillant: Getting started with DirectX 11](https://rodolphe-vaillant.fr/entry/121/getting-started-with-directx-11)
- [MSDN: Module 1. Your First Windows Program](https://learn.microsoft.com/en-us/windows/win32/learnwin32/your-first-windows-program)
- [Joseph Whittington: Basic DirectX 11 tutorial, Visual Studio 2019, Win32 Window API Tutorial](https://web.archive.org/web/20231203194918/https://dev.to/josephwhittington/setup-d3d11-in-visual-studio-2019-423g) (Pretty bad. Also requires the DirectX SDK.)
- [About-prog: DirectX 11 Initialization, First Triangle](https://web.archive.org/web/20211127054316/https://about-prog.com/directx11/direct3d-11-init-and-triangle-rendering) - (Doesn't cover windowing or any full code samples. Requires the DirectX SDK as mentioned.)
- [RasterTek - DirectX 11 on Windows 10 tutorials](https://www.rastertek.com/tutdx11win10.html) (Very comprehensive, but uses a lot of weird C++ practices, code structuring choices and design decisions. Previously required the obsolete DirectX SDK, but has recently been updated to remove that requirement and use Visual Studio 2022.)
- [BraynzarSoft - DirectX 11 Tutorials](https://www.braynzarsoft.net/viewtutorial/q16390-braynzar-soft-directx-11-tutorials) (Uses Visual Studio 2010.)
- [bell0bytes - Game Programming](https://bell0bytes.eu/gamedev/gamedev/) (Doesn't cover 3D rendering, which is unfortunate for some. Developed from Visual Studio 2017 to 2019.)
- [3dgep: Introduction to DirectX 11](https://www.3dgep.com/introduction-to-directx-11/)
- [3dgep: Texturing and Lighting in DirectX 11](https://www.3dgep.com/texturing-lighting-directx-11/)
- [3dgep: Forward vs Deferred vs Forward+ Rendering with DirectX 11](https://www.3dgep.com/forward-plus/) (Includes code samples throughout, though not the complete source code at the end.)
- [TutorialsPoint - DirectX](https://www.tutorialspoint.com/directx/index.htm) (Should probably avoid. An unstructured heap of random DirectX documentation without any samples or examples.)
- [NVIDIA GameWorks - Direct3D Graphics/Compute Samples](https://docs.nvidia.com/gameworks/content/gameworkslibrary/graphicssamples/d3d_samples/d3d_samples.htm) - (They have explanations, but I haven't found the source code yet.)

## Books
- [Chris Rose: Direct3D Succintly, 2014](https://www.syncfusion.com/ebooks/direct3d) - (Requires Visual Studio 2012 in order to follow. The ebook can either be downloaded or read online.)

## Courses
- [Udemy, Ole Holthe: DirectX 11 Programming](https://www.udemy.com/course/directx11/?couponCode=SKILLS4SALEA) (Highest price: $39.99. Outdated, uses Visual Studio 2010 but also contains a chapter for converting to Visual Studio 2012.)

## Repositories
- [brainexcerpts: winAPI_basic_window](https://github.com/brainexcerpts/winAPI_basic_window)
- [DXUT](https://github.com/microsoft/DXUT)
- [ImGui: Win32 setup](https://github.com/ocornut/imgui/blob/master/examples/example_win32_directx11/main.cpp) (Example implementation of ImGui into a Win32 DirectX 11 application.)
- [ImGui: SDL setup](https://github.com/ocornut/imgui/blob/master/examples/example_sdl_directx11/main.cpp) (Example implementation of ImGui into an SDL DirectX 11 application.)
- [Joseph Whittington: Basic DirectX 11 tutorial, Visual Studio 2019, Win32 Window API Codebase](https://web.archive.org/web/20231224115319/https://github.com/josephwhittington/tutorial_1_d3d11_setup) (Archive of the repository for Joseph Whittington's tutorial.)
- [brainexcerpts: Dxerr](https://github.com/brainexcerpts/Dxerr)
- [Matt77hias: RasterTek](https://github.com/matt77hias/RasterTek) (Port of the old RasterTek DirectX 11 tutorials for Visual Studio 2017.)

## YouTube
- [Avoyd: RCC++ ImGui and DirectX 11 Tutorial](https://www.youtube.com/watch?v=5lOOLHmQPBU&list=PLOV2v_nVCDf5tyP3mc1G7vMb7TWVhxDIA&index=1) (Tutorial series on setting up runtime-compiled-C++ to use ImGui with DirectX 11.)
- [ChiliTomatoNoodle: DirectX 11 C++ Tutorial Series](https://www.youtube.com/watch?v=_4FArgOX1I4&list=PLqCJpWy5Fohd3S7ICFXwUomYW0Wv67pDD) (Highly informal and uses crass language. Focuses a lot more on the explanation but does some coding as well. Warning that tons of the code has been written intentionally before recording.)
- [Jpres: C++ DirectX 11 Engine Tutorial](https://www.youtube.com/watch?v=gQIG77PfLgo&list=PLcacUGyBsOIBlGyQQWzp6D1Xn6ZENx9Y2&index=1) (Similar to ChiliTomatoNoodle's tutorial series, but uses the DirectXTK. Jpres doesn't cover topics like shadow mapping or advanced lighting. Instead, the series focuses more on things like input and error handling. Also quite informal but not as vulgar. As mentioned earlier, it uses the DirectXTK (DirectX toolkit) to simplify some parts of the process.)
- [Matt Guerrette: DirectX 11 Tutorial Series](https://youtube.com/playlist?list=PL0DPXkWsyQQYv4Zuz0nB0XN3c2MZLeycq&si=bU1Qa5KqXVj_VJa_) (Very likely incomplete or abandoned.)
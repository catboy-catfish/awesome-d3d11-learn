# awesome-d3d
A curated list designed to aggregate some awesome resources on learning how to use the Direct3D graphics API. Mostly deals with DX11/D3D11 or DX12/D3D12.

I created this list due to not being able to easily find as much information for programming with Direct3D as I could for OpenGL or Vulkan.

I hope this helps as much as it's helping me.

# D3D 11
## Articles
- [Rodolphe Vaillant: Getting started with DirectX 11](https://rodolphe-vaillant.fr/entry/121/getting-started-with-directx-11) - Original page that aggregates a lot of the links listed in this section.
- [MSDN: Module 1. Your First Windows Program](https://learn.microsoft.com/en-us/windows/win32/learnwin32/your-first-windows-program) - Microsoft's article walking you through how to create your first windows program using the Win32 API.
- [Joseph Whittington: Basic DirectX 11 tutorial, Visual Studio 2019, Win32 Window API Tutorial](https://web.archive.org/web/20231203194918/https://dev.to/josephwhittington/setup-d3d11-in-visual-studio-2019-423g) - Archive of Joseph Whittington's tutorial on how to set up Direct3D 11. Pretty bad. Requires the DirectX SDK as he mentions.
- [About-prog: DirectX 11 Initialization, First Triangle](https://web.archive.org/web/20211127054316/https://about-prog.com/directx11/direct3d-11-init-and-triangle-rendering) - Archive of About-prog's rough tutorial on how to initialize DirectX and draw a triangle. Doesn't cover windowing or any full code samples. Requires the DirectX SDK as mentioned.
## Repositories
- [brainexcerpts: winAPI_basic_window](https://github.com/brainexcerpts/winAPI_basic_window) - Vaillant's example of the creation of a window using the Windows API.
- [DXUT](https://github.com/microsoft/DXUT) - a GLUT-like DirectX window manager well suited for sample code or demos.
- [ImGui: Win32 setup](https://github.com/ocornut/imgui/blob/master/examples/example_win32_directx11/main.cpp) - Example implementation of ImGui into a Win32 DirectX 11 application.
- [ImGui: SDL setup](https://github.com/ocornut/imgui/blob/master/examples/example_sdl_directx11/main.cpp) - Example implementation of ImGui into an SDL DirectX 11 application.
- [Joseph Whittington: Basic DirectX 11 tutorial, Visual Studio 2019, Win32 Window API Codebase](https://web.archive.org/web/20231224115319/https://github.com/josephwhittington/tutorial_1_d3d11_setup) - Archive of the repository for Joseph Whittington's tutorial on how to set up DirectX 11. Pretty bad. Requires the DirectX SDK as mentioned in the original article.
- [brainexcerpts: Dxerr](https://github.com/brainexcerpts/Dxerr) - Vaillant's repository for the dxerr (DirectX error library) source code which converts different HRESULTS into more readable formats.
## YouTube
- [ChiliTomatoNoodle: DirectX C++ Tutorial Series](https://www.youtube.com/watch?v=_4FArgOX1I4&list=PLqCJpWy5Fohd3S7ICFXwUomYW0Wv67pDD) - Tutorial series on using Direct3D 11 to make a rather simple 3D renderer in C++. Deals with windowing, error handling, D3D11 initialization, triangle drawing, 3D rendering, asset importing, asset loading, HLSL shading, lighting, shadow mapping, using ImGui and more. Highly informal and uses crass language. Focuses a lot more on the explanation but does some coding as well. Warning that tons of the code has been written before recording.
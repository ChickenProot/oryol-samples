fips_begin_app(ImGuiDemo windowed)
    fips_vs_warning_level(3)
    fips_files(
        ImGuiDemo.cc
    )
    fips_deps(Gfx IMUI)
    oryol_add_web_sample(ImGuiDemo "ImGui UI integration" "emscripten" ImGuiDemo.jpg "ImGuiDemo/ImGuiDemo.cc")
fips_end_app()

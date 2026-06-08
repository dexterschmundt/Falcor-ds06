add_plugin(DirectPhotonMapper)

target_sources(DirectPhotonMapper PRIVATE
    DirectPhotonMapper.cpp
    DirectPhotonMapper.h
)

target_source_group(DirectPhotonMapper "RenderPasses")

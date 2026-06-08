add_plugin(DirectPhotonMapper)

target_sources(DirectPhotonMapper PRIVATE
    DirectPhotonMapper.cpp
    DirectPhotonMapper.h
    LightSampler.slang
)

target_source_group(DirectPhotonMapper "RenderPasses")

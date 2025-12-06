target_sources(amr101 PRIVATE
    AdvancePhiAllLevels.cpp
    AdvancePhiAtLevel.cpp
    AmrCoreAdv.cpp
    AmrCoreAdv.H
    bc_fill.H
    DefineVelocity.cpp
    face_velocity.H
    Kernels.H
    main.cpp
    Tagging.H
    Src_K/Adv_K.H
    Src_K/compute_flux_3D_K.H
    Src_K/slope_K.H
)

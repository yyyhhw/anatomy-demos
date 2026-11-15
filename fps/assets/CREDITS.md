# 资产来源与授权 / Asset credits

## Poly Haven — CC0 1.0（公有领域，可自由使用）
https://polyhaven.com/license

模型 `models/*.glb`（已缩放贴图、转 WebP、网格量化，部分做了减面）：
bolt_action_rifle_7_62, service_pistol, stick_grenade, modular_factory_facade,
concrete_road_barrier, concrete_road_barrier_02, old_military_crate,
wooden_military_crate, wooden_crate_02, ammo_box, Barrel_01, Barrel_02,
barrel_03, metal_jerrycan_green, old_tyre, utility_box_01, covered_car,
portable_generator, metal_trash_can, propane_tank, cement_bag, trashbag,
security_light, water_manhole_cover, modular_fire_escape,
modular_industrial_pipes_01, exterior_aircon_unit, hand_truck,
security_camera_01

PBR 贴图 `tex/*`：
asphalt_02, concrete_pavement, concrete_wall_008, damaged_plaster,
worn_brick_wall, container_side, corrugated_iron_02, concrete_floor_worn_001,
green_metal_rust, metal_plate, hessian_230, bitumen

天空 `sky/*`（由 4K HDRI 取上半球并编码为 WebP）：
- day: kloofendal_48d_partly_cloudy_puresky
- dusk: belfast_sunset_puresky
- night: qwantani_moonrise_puresky

## three.js 示例资产
`models/soldier.glb`：three.js 仓库 `examples/models/gltf/Soldier.glb`
（Mixamo 角色 “Vanguard”，含 Idle / Walk / Run 动画）。
Mixamo 角色与动画可免费用于个人和商业项目；如需单独再分发原始文件，
请遵循 Adobe Mixamo 的条款。

## 引擎
three.js r160（MIT），运行时从 cdn.jsdelivr.net 加载。

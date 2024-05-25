# DishWasher

Calculate the dimesions of an object (cm)
```bash
import omni.isaac.core.utils.bounds as bounds_utils

cache = bounds_utils.create_bbox_cache()
bounds = bounds_utils.compute_aabb(cache, prim_path="/Root/bin/Visuals/FOF_Mesh_Magenta_Box")

length_x = bounds[3] - bounds[0]
length_y = bounds[4] - bounds[1]
length_z = bounds[5] - bounds[2]

print("length of x:",length_x)
print("length of y:",length_y)
print("length of z:",length_z)
```


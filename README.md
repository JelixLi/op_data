# Data Format
Cpu Nums,MPS,Batch Size,Host/device,Type,Avg. time (us),Shape
# Data Field Explanation
Cpu Nums: number of cpu cores(with hyper threading).
MPS: Nvidia MPS((Multi process service) active thread percentage.
Batch Size: number of inputs in a batch.
Host/device: denote where the operation executes(host(CPU) or Device(GPU))
Avg. time(us): time the operation executes in micro seconds.
Shape: shape of the inputs of the operation.

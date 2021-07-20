include_directories(src)
add_executable(agent src/platform.c src/provider.c src/remote.c src/provider_handler.c src/consumer.c src/consumer_handler.c src/device.c src/forward.c src/id.c src/loadbalancer.c src/main.c src/object.c src/opencl_cmdqueue.c  src/opencl_context.c src/opencl_device.c src/opencl_event.c src/opencl_kernel.c src/opencl_memobj.c src/opencl_program.c src/agent.c)

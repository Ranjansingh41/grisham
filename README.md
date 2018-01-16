# grisham

## Platform Test Matrix

- testing the core features of build platform

|Features/arch-os|x86_u14|x86_u16|aarch_u16|x86_mac10|x86_win16|
|---|---|---|---|---|---|
|jobs on host|x|x|||
|jobs on host with custom ENVS|x|x|||
|jobs on host without errors execute on_success and always|x|x|||
|jobs on host with errors|x|x|||
|jobs on host with errors execute on_failure and always|x|x|||
|jobs on host timing out|||||
|jobs on host cancellation|||||
|jobs on host sharing state b/w tasks|x|x|||
|---|---|---|---|---|---|
|jobs on default image|x|x|||
|jobs on default image with ENVS|x|x|||
|jobs on default image with runtime params|||||
|jobs on default image without errors execute on_success and always|x|x|||
|jobs on default image with errors|x|x|||
|jobs on default image with errors execute on_failure and always|x|x|||
|jobs on default image timing out|x|x|||
|jobs on default image cancellation|||||
|jobs on default image sharing state b/w tasks|x|x|||
|---|---|---|---|---|---|
|jobs on custom image|x|x|||
|jobs on custom image with ENVS|x|x|||
|jobs on custom image without errors execute on_success and always|x|x|||
|jobs on custom image with runtime params|||||
|jobs on custom image with errors|x|x|||
|jobs on custom image with errors execute on_failure and always|x|x|||
|jobs on custom image timing out|||||
|jobs on custom image cancellation|||||

## Job functionality test matrix

|Functionality/os|x86_u14|x86_u16|aarch_u16|x86_mac10|x86_win16|
|---|---|---|---|---|---|
|pre task notifications||||||
|IN processing||||||
|OUT processing||||||
|global state||||||

################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/TI/ccsv6/tools/compiler/ti-cgt-arm_5.2.9

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./Font_lib.obj" \
"./LCD_TFT_ILI9341.obj" \
"./LCD_display.obj" \
"./SHT2X.obj" \
"./bma222drv.obj" \
"./device_status.obj" \
"./gpio_if.obj" \
"./i2c_if.obj" \
"./main.obj" \
"./network_common.obj" \
"./pinmux.obj" \
"./smartconfig.obj" \
"./startup_ccs.obj" \
"./timer_if.obj" \
"./tmp006drv.obj" \
"./uart_if.obj" \
"../cc3200v1p32.cmd" \
$(GEN_CMDS__FLAG) \
-llibc.a \
-ldriverlib.a \
-lsimplelink.a \
-lfree_rtos.a \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
2024_2050971_final.out \

EXE_OUTPUTS__QUOTED += \
"2024_2050971_final.out" \

BIN_OUTPUTS += \
2024_2050971_final.bin \

BIN_OUTPUTS__QUOTED += \
"2024_2050971_final.bin" \


# All Target
all: 2024_2050971_final.out

# Tool invocations
2024_2050971_final.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: ARM Linker'
	"C:/TI/ccsv6/tools/compiler/ti-cgt-arm_5.2.9/bin/armcl" -mv7M4 --code_state=16 --float_support=vfplib --abi=eabi -me -g --gcc --define=ccs --define=SL_PLATFORM_MULTI_THREADED --define=USE_FREERTOS --define=cc3200 --diag_warning=225 --diag_wrap=off --display_error_number -z -m"2024_2050971_final.map" --stack_size=0x1000 --heap_size=0x2000 -i"C:/TI/ccsv6/tools/compiler/ti-cgt-arm_5.2.9/lib" -i"C:/TI/ccsv6/tools/compiler/ti-cgt-arm_5.2.9/include" -i"C:/ti/CC3200SDK_1.2.0/cc3200-sdk/driverlib/ccs/Release" -i"C:/ti/CC3200SDK_1.2.0/cc3200-sdk/simplelink/ccs/OS" -i"C:/ti/CC3200SDK_1.2.0/cc3200-sdk/oslib/ccs/free_rtos" --reread_libs --diag_wrap=off --display_error_number --warn_sections --xml_link_info="2024_2050971_final_linkInfo.xml" --rom_model -o "2024_2050971_final.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

2024_2050971_final.bin: $(EXE_OUTPUTS)
	@echo 'Invoking: ARM Hex Utility'
	"C:/TI/ccsv6/tools/compiler/ti-cgt-arm_5.2.9/bin/armhex"  -o "2024_2050971_final.bin" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "Font_lib.d" "LCD_TFT_ILI9341.d" "LCD_display.d" "SHT2X.d" "bma222drv.d" "device_status.d" "gpio_if.d" "i2c_if.d" "main.d" "network_common.d" "pinmux.d" "smartconfig.d" "startup_ccs.d" "timer_if.d" "tmp006drv.d" "uart_if.d" 
	-$(RM) "Font_lib.obj" "LCD_TFT_ILI9341.obj" "LCD_display.obj" "SHT2X.obj" "bma222drv.obj" "device_status.obj" "gpio_if.obj" "i2c_if.obj" "main.obj" "network_common.obj" "pinmux.obj" "smartconfig.obj" "startup_ccs.obj" "timer_if.obj" "tmp006drv.obj" "uart_if.obj" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-@echo 'convert to bin files'
	-"C:/TI/ccsv6/utils/tiobj2bin/tiobj2bin" "2024_2050971_final.out" "2024_2050971_final.bin" "C:/TI/ccsv6/tools/compiler/ti-cgt-arm_5.2.9/bin/armofd" "C:/TI/ccsv6/tools/compiler/ti-cgt-arm_5.2.9/bin/armhex" "C:/TI/ccsv6/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: post-build

-include ../makefile.targets


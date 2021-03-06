# Copyright (c) 2017 Erwin Rol <erwin@erwinrol.com>
#
# SPDX-License-Identifier: Apache-2.0

zephyr_library_sources(soc/system_stm32f1xx.c)
zephyr_library_sources(drivers/src/stm32f1xx_hal.c)
zephyr_library_sources(drivers/src/stm32f1xx_hal_rcc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_ADC drivers/src/stm32f1xx_hal_adc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_ADC_EX drivers/src/stm32f1xx_hal_adc_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_CAN drivers/src/stm32f1xx_hal_can.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_CEC drivers/src/stm32f1xx_hal_cec.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_CORTEX drivers/src/stm32f1xx_hal_cortex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_CRC drivers/src/stm32f1xx_hal_crc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_DAC drivers/src/stm32f1xx_hal_dac.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_DAC_EX drivers/src/stm32f1xx_hal_dac_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_DMA drivers/src/stm32f1xx_hal_dma.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_ETH drivers/src/stm32f1xx_hal_eth.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_FLASH drivers/src/stm32f1xx_hal_flash.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_FLASH_EX drivers/src/stm32f1xx_hal_flash_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_GPIO drivers/src/stm32f1xx_hal_gpio.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_GPIO_EX drivers/src/stm32f1xx_hal_gpio_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_HCD drivers/src/stm32f1xx_hal_hcd.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_I2C drivers/src/stm32f1xx_hal_i2c.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_I2S drivers/src/stm32f1xx_hal_i2s.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_IRDA drivers/src/stm32f1xx_hal_irda.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_IWDG drivers/src/stm32f1xx_hal_iwdg.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_MMC drivers/src/stm32f1xx_hal_mmc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_NAND drivers/src/stm32f1xx_hal_nand.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_NOR drivers/src/stm32f1xx_hal_nor.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_PCCARD drivers/src/stm32f1xx_hal_pccard.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_PCD drivers/src/stm32f1xx_hal_pcd.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_PCD_EX drivers/src/stm32f1xx_hal_pcd_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_PWR drivers/src/stm32f1xx_hal_pwr.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_RCC_EX drivers/src/stm32f1xx_hal_rcc_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_RTC drivers/src/stm32f1xx_hal_rtc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_RTC_EX drivers/src/stm32f1xx_hal_rtc_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_SD drivers/src/stm32f1xx_hal_sd.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_SMARTCARD drivers/src/stm32f1xx_hal_smartcard.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_SPI drivers/src/stm32f1xx_hal_spi.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_SPI_EX drivers/src/stm32f1xx_hal_spi_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_SRAM drivers/src/stm32f1xx_hal_sram.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_TIM drivers/src/stm32f1xx_hal_tim.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_TIM_EX drivers/src/stm32f1xx_hal_tim_ex.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_UART drivers/src/stm32f1xx_hal_uart.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_USART drivers/src/stm32f1xx_hal_usart.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_HAL_WWDG drivers/src/stm32f1xx_hal_wwdg.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_ADC drivers/src/stm32f1xx_ll_adc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_CRC drivers/src/stm32f1xx_ll_crc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_DAC drivers/src/stm32f1xx_ll_dac.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_DMA drivers/src/stm32f1xx_ll_dma.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_EXTI drivers/src/stm32f1xx_ll_exti.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_FSMC drivers/src/stm32f1xx_ll_fsmc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_GPIO drivers/src/stm32f1xx_ll_gpio.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_I2C drivers/src/stm32f1xx_ll_i2c.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_PWR drivers/src/stm32f1xx_ll_pwr.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_RCC drivers/src/stm32f1xx_ll_rcc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_RTC drivers/src/stm32f1xx_ll_rtc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_SDMMC drivers/src/stm32f1xx_ll_sdmmc.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_SPI drivers/src/stm32f1xx_ll_spi.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_TIM drivers/src/stm32f1xx_ll_tim.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_USART drivers/src/stm32f1xx_ll_usart.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_USB drivers/src/stm32f1xx_ll_usb.c)
zephyr_library_sources_ifdef(CONFIG_USE_STM32_LL_UTILS drivers/src/stm32f1xx_ll_utils.c)


obj-$(CONFIG_SMCDSD_PANEL) += ../smcdsd_panel_init.o ../smcdsd_panel.o ../smcdsd_board.o ../smcdsd_notify.o ../smcdsd_abd.o

obj-$(CONFIG_SMCDSD_DPUI) += dpui.o
obj-$(CONFIG_SMCDSD_MDNIE) += mdnie.o

obj-$(and $(CONFIG_SMCDSD_MDNIE),$(CONFIG_SMCDSD_LCD_DEBUG),$(subst undefined,y,$(origin CONFIG_SAMSUNG_PRODUCT_SHIP))) += dd_mdnie.o
obj-$(and $(CONFIG_SMCDSD_LCD_DEBUG),$(subst undefined,y,$(origin CONFIG_SAMSUNG_PRODUCT_SHIP))) += dd_lcd.o dd_backlight.o dd_param.o

obj-$(CONFIG_SMCDSD_PANEL_A32)	+= s6e3fc3_a32.o
obj-$(CONFIG_SMCDSD_PANEL_M32)	+= s6e3fc3_m32.o
obj-$(CONFIG_SMCDSD_PANEL_A22)	+= s6e3fc3_a22.o s6e3fc3_a32.o
obj-$(CONFIG_SMCDSD_PANEL_A31)	+= ea8076_a31.o timenval.o
obj-$(CONFIG_SMCDSD_PANEL_A41)	+= ea8076_a31.o timenval.o
obj-$(CONFIG_SMCDSD_PANEL_A41_JPN)	+= ea8076_a31.o timenval.o


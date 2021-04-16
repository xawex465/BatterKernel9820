# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos9820.dtb
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_26.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_19.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_17.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_18.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_24.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_16.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_23.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_04.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_25.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND2) += samsung/exynos9820-beyond2lte_eur_open_20.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_17.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_18.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_19.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_20.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_21.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_22.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_23.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_24.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND1) += samsung/exynos9820-beyond1lte_eur_open_26.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND0) += samsung/exynos9820-beyond0lte_eur_open_22.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND0) += samsung/exynos9820-beyond0lte_eur_open_18.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND0) += samsung/exynos9820-beyond0lte_eur_open_17.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND0) += samsung/exynos9820-beyond0lte_eur_open_19.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND0) += samsung/exynos9820-beyond0lte_eur_open_24.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND0) += samsung/exynos9820-beyond0lte_eur_open_25.dtbo
dtbo-$(CONFIG_9820_DTS_BEYOND0) += samsung/exynos9820-beyond0lte_eur_open_20.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*

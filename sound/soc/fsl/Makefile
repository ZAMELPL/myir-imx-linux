# SPDX-License-Identifier: GPL-2.0
# MPC8610 HPCD Machine Support
snd-soc-mpc8610-hpcd-objs := mpc8610_hpcd.o
obj-$(CONFIG_SND_SOC_MPC8610_HPCD) += snd-soc-mpc8610-hpcd.o

# P1022 DS Machine Support
snd-soc-p1022-ds-objs := p1022_ds.o
obj-$(CONFIG_SND_SOC_P1022_DS) += snd-soc-p1022-ds.o

# P1022 RDK Machine Support
snd-soc-p1022-rdk-objs := p1022_rdk.o
obj-$(CONFIG_SND_SOC_P1022_RDK) += snd-soc-p1022-rdk.o

# Freescale SSI/DMA/SAI/SPDIF Support
snd-soc-fsl-audmix-objs := fsl_audmix.o
snd-soc-fsl-dsp-audiomix-objs := fsl_dsp_audiomix.o
snd-soc-fsl-asrc-objs := fsl_asrc.o fsl_asrc_dma.o
snd-soc-fsl-dsp-objs := fsl_dsp.o fsl_dsp_proxy.o fsl_dsp_pool.o \
	fsl_dsp_library_load.o fsl_dsp_xaf_api.o fsl_dsp_cpu.o \
	fsl_dsp_platform_compress.o
snd-soc-fsl-sai-objs := fsl_sai.o
snd-soc-fsl-ssi-y := fsl_ssi.o
snd-soc-fsl-ssi-$(CONFIG_DEBUG_FS) += fsl_ssi_dbg.o
snd-soc-fsl-spdif-objs := fsl_spdif.o
snd-soc-fsl-esai-objs := fsl_esai.o
snd-soc-fsl-dai-objs := fsl_dai.o
snd-soc-fsl-micfil-objs := fsl_micfil.o
snd-soc-fsl-utils-objs := fsl_utils.o
snd-soc-fsl-dma-objs := fsl_dma.o
snd-soc-fsl-easrc-objs := fsl_easrc.o fsl_easrc_dma.o
snd-soc-fsl-aud2htx-objs := fsl_aud2htx.o
snd-soc-fsl-xcvr-objs := fsl_xcvr.o

obj-$(CONFIG_SND_SOC_FSL_AUDMIX) += snd-soc-fsl-audmix.o
snd-soc-fsl-asoc-card-objs := fsl-asoc-card.o
snd-soc-fsl-rpmsg-i2s-objs := fsl_rpmsg_i2s.o
obj-$(CONFIG_SND_SOC_FSL_ASOC_CARD) += snd-soc-fsl-asoc-card.o
snd-soc-fsl-hdmi-objs := fsl_hdmi.o
obj-$(CONFIG_SND_SOC_FSL_ASRC) += snd-soc-fsl-asrc.o
obj-$(CONFIG_SND_SOC_FSL_DSP) += snd-soc-fsl-dsp.o
obj-$(CONFIG_SND_SOC_FSL_DSP_AUDIOMIX) += snd-soc-fsl-dsp-audiomix.o
obj-$(CONFIG_SND_SOC_FSL_SAI) += snd-soc-fsl-sai.o
obj-$(CONFIG_SND_SOC_FSL_SSI) += snd-soc-fsl-ssi.o
obj-$(CONFIG_SND_SOC_FSL_SPDIF) += snd-soc-fsl-spdif.o
obj-$(CONFIG_SND_SOC_FSL_ESAI) += snd-soc-fsl-esai.o
obj-$(CONFIG_SND_SOC_FSL_DAI) += snd-soc-fsl-dai.o
obj-$(CONFIG_SND_SOC_FSL_MICFIL) += snd-soc-fsl-micfil.o
obj-$(CONFIG_SND_SOC_FSL_UTILS) += snd-soc-fsl-utils.o
obj-$(CONFIG_SND_SOC_FSL_HDMI) += snd-soc-fsl-hdmi.o
obj-$(CONFIG_SND_SOC_POWERPC_DMA) += snd-soc-fsl-dma.o
obj-$(CONFIG_SND_SOC_FSL_EASRC) += snd-soc-fsl-easrc.o
obj-$(CONFIG_SND_SOC_FSL_ASOC_CARD) += snd-soc-fsl-asoc-card.o
obj-$(CONFIG_SND_SOC_FSL_RPMSG_I2S) += snd-soc-fsl-rpmsg-i2s.o
obj-$(CONFIG_SND_SOC_FSL_AUD2HTX) += snd-soc-fsl-aud2htx.o
obj-$(CONFIG_SND_SOC_FSL_XCVR) += snd-soc-fsl-xcvr.o

# MPC5200 Platform Support
obj-$(CONFIG_SND_MPC52xx_DMA) += mpc5200_dma.o
obj-$(CONFIG_SND_SOC_MPC5200_I2S) += mpc5200_psc_i2s.o
obj-$(CONFIG_SND_SOC_MPC5200_AC97) += mpc5200_psc_ac97.o

# MPC5200 Machine Support
obj-$(CONFIG_SND_MPC52xx_SOC_PCM030) += pcm030-audio-fabric.o
obj-$(CONFIG_SND_MPC52xx_SOC_EFIKA) += efika-audio-fabric.o

# i.MX Platform Support
snd-soc-imx-ssi-objs := imx-ssi.o
snd-soc-imx-audmux-objs := imx-audmux.o
obj-$(CONFIG_SND_SOC_IMX_SSI) += snd-soc-imx-ssi.o
obj-$(CONFIG_SND_SOC_IMX_AUDMUX) += snd-soc-imx-audmux.o

obj-$(CONFIG_SND_SOC_IMX_PCM_FIQ) += imx-pcm-fiq.o
obj-$(CONFIG_SND_SOC_IMX_PCM_DMA) += imx-pcm-dma.o imx-pcm-dma-v2.o
obj-$(CONFIG_SND_SOC_IMX_PCM_DMA) += imx-pcm-dma.o
obj-$(CONFIG_SND_SOC_IMX_HDMI_DMA) += imx-hdmi-dma.o hdmi_pcm.o
obj-$(CONFIG_SND_SOC_IMX_PCM_RPMSG) += imx-pcm-rpmsg.o

# i.MX Machine Support
snd-soc-eukrea-tlv320-objs := eukrea-tlv320.o
snd-soc-phycore-ac97-objs := phycore-ac97.o
snd-soc-mx27vis-aic32x4-objs := mx27vis-aic32x4.o
snd-soc-wm1133-ev1-objs := wm1133-ev1.o
snd-soc-imx-es8328-objs := imx-es8328.o
snd-soc-imx-cs42888-objs := imx-cs42888.o
snd-soc-imx-sgtl5000-objs := imx-sgtl5000.o
snd-soc-imx-wm8958-objs := imx-wm8958.o
snd-soc-imx-wm8960-objs := imx-wm8960.o
snd-soc-imx-wm8904-objs := imx-wm8904.o
snd-soc-imx-wm8524-objs := imx-wm8524.o
snd-soc-imx-wm8962-objs := imx-wm8962.o
snd-soc-imx-sii902x-objs := imx-sii902x.o
snd-soc-imx-spdif-objs := imx-spdif.o
snd-soc-imx-mc13783-objs := imx-mc13783.o
snd-soc-imx-audmix-objs := imx-audmix.o
snd-soc-imx-mqs-objs := imx-mqs.o
snd-soc-imx-pdm-objs := imx-pdm.o
snd-soc-imx-ak4458-objs := imx-ak4458.o
snd-soc-imx-ak5558-objs := imx-ak5558.o
snd-soc-imx-ak4497-objs := imx-ak4497.o
snd-soc-imx-micfil-objs := imx-micfil.o
snd-soc-imx-dsp-objs := imx-dsp.o
snd-soc-imx-si476x-objs := imx-si476x.o
snd-soc-imx-hdmi-objs := imx-hdmi.o
snd-soc-imx-cdnhdmi-objs := imx-cdnhdmi.o
snd-soc-imx-rpmsg-objs := imx-rpmsg.o
snd-soc-imx-xcvr-objs := imx-xcvr.o

obj-$(CONFIG_SND_SOC_EUKREA_TLV320) += snd-soc-eukrea-tlv320.o
obj-$(CONFIG_SND_SOC_PHYCORE_AC97) += snd-soc-phycore-ac97.o
obj-$(CONFIG_SND_SOC_MX27VIS_AIC32X4) += snd-soc-mx27vis-aic32x4.o
obj-$(CONFIG_SND_MXC_SOC_WM1133_EV1) += snd-soc-wm1133-ev1.o
obj-$(CONFIG_SND_SOC_IMX_ES8328) += snd-soc-imx-es8328.o
obj-$(CONFIG_SND_SOC_IMX_CS42888) += snd-soc-imx-cs42888.o
obj-$(CONFIG_SND_SOC_IMX_SGTL5000) += snd-soc-imx-sgtl5000.o
obj-${CONFIG_SND_SOC_IMX_WM8958} += snd-soc-imx-wm8958.o
obj-$(CONFIG_SND_SOC_IMX_WM8960) += snd-soc-imx-wm8960.o
obj-$(CONFIG_SND_SOC_IMX_WM8904) += snd-soc-imx-wm8904.o
obj-$(CONFIG_SND_SOC_IMX_WM8524) += snd-soc-imx-wm8524.o
obj-$(CONFIG_SND_SOC_IMX_WM8962) += snd-soc-imx-wm8962.o
obj-$(CONFIG_SND_SOC_IMX_SII902X) += snd-soc-imx-sii902x.o
obj-$(CONFIG_SND_SOC_IMX_RPMSG) += snd-soc-imx-rpmsg.o
obj-$(CONFIG_SND_SOC_IMX_SPDIF) += snd-soc-imx-spdif.o
obj-$(CONFIG_SND_SOC_IMX_MC13783) += snd-soc-imx-mc13783.o
obj-$(CONFIG_SND_SOC_IMX_AUDMIX) += snd-soc-imx-audmix.o
obj-$(CONFIG_SND_SOC_IMX_MQS) += snd-soc-imx-mqs.o
obj-$(CONFIG_SND_SOC_IMX_PDM_MIC) += snd-soc-imx-pdm.o
obj-$(CONFIG_SND_SOC_IMX_AK4458) += snd-soc-imx-ak4458.o
obj-$(CONFIG_SND_SOC_IMX_AK5558) += snd-soc-imx-ak5558.o
obj-$(CONFIG_SND_SOC_IMX_AK4497) += snd-soc-imx-ak4497.o
obj-$(CONFIG_SND_SOC_IMX_MICFIL) += snd-soc-imx-micfil.o
obj-$(CONFIG_SND_SOC_IMX_DSP) += snd-soc-imx-dsp.o
obj-$(CONFIG_SND_SOC_IMX_SI476X) += snd-soc-imx-si476x.o
obj-$(CONFIG_SND_SOC_IMX_HDMI) += snd-soc-imx-hdmi.o
obj-$(CONFIG_SND_SOC_IMX_CDNHDMI) += snd-soc-imx-cdnhdmi.o
obj-$(CONFIG_SND_SOC_IMX_XCVR) += snd-soc-imx-xcvr.o

AFLAGS_hdmi_pcm.o := -march=armv7-a -mtune=cortex-a9 -mfpu=neon -mfloat-abi=softfp

# CHEN, Yenchia

Software Engineer & Saturday Artist (*an amateur's amateur*)

### Device Tree Binding: `arch/arm64/boot/dts/mediatek/chiaracter.dts`

```dts
chiaracter@2024 {
    /* Chiaroscuro forms the core architectural base of realism */
    compatible = "chiaroscuro,art-v1";
    model = "Online Gallery";
    reg = <0x20240000 0x1000>;          /* Project launched in 2024 */

    /* Secondary processing cluster via gemini_ai_core */
    coprocessor = <&gemini_ai_core>;

    /* Character interrupts routed and modulated via yenchia-tx */
    interrupt-parent = <&character_gic>;
    interrupts = <4 1>;                 /* IRQ 4: Unexpected pop-culture intrusion */
    interrupt-names = "yenchia-tx";     /* Channel for luminance contrast data */

    status = "okay";
};

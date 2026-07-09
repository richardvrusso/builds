# unRAID Compute Server
Taking a play from my enterprise world. This is a compute server only running Docker and VMs.

[Cooler Master MasterBox Q300L Micro-ATX Tower](https://www.amazon.com/dp/B0785GRMPG?ref=ppx_yo2ov_dt_b_fed_asin_title){:target="_blank"}
[SUPERMICRO X10SRM-F Micro ATX Server Motherboard R3 (LGA 2011) Intel C612](https://www.newegg.com/supermicro-x10srm-f-single-socket-r3-support-intel-xeon-processor-e5-2600-v4-v3-e5-1600-v4-v3/p/N82E16813183597){:target="_blank"}
[Intel Xeon E5-2650 V4 SR2N3 12-Core 2.2GHz 30MB LGA 2011-3 Processor](https://www.amazon.com/gp/product/B07P12XK2J){:target="_blank"}
[SK HYNIX 32GB HMA84GR7MFR4N-UH DDR4-2400 ECC RDIMM 2Rx4 PC4-19200T-R CL17 Server Memory](https://www.amazon.com/gp/product/B07XCXS7MH){:target="_blank"}
128GB of ECC RAM
[Rapid Technologies Toshiba KXG60ZNV256G 3MM Height 256GB 80MM Length M.2 Single Sided TLC NVMe](https://www.amazon.com/gp/product/B082P8YFPW){:target="_blank"}
2 for a mirrored cache to run dockers/vm's.

Crucial P3 1TB PCIe Gen3 3D NAND NVMe M.2 SSD, up to 3500MB/s - CT1000P3SSD8	http://www.amazon.com/gp/product/B0B25LZGGW	Cache dedicated to downloads/extractions.
Intel SSD DC S4500 1.92TB 3D TLC SATA 6Gb/s 2.5-Inch x 7mm Enterprise Solid State Drive (SSDSC2KB019T701)	http://www.amazon.com/gp/product/B074QSB52M	1 drive for the array as overflow protection if cache drives fill up.
be quiet! Shadow Wings 2 120mm PWM Silent Low Noise Cooling Fan | Low Noise Operation | Rubber Fan Frame | Designed in Germany | Black | BL	https://www.amazon.com/dp/B07MCHLGC5?ref=ppx_yo2ov_dt_b_fed_asin_title	Front and rear fans for the case.
Noctua NH-D9DX i4 3U, Premium CPU Cooler for Intel Xeon LGA20xx (92mm, Brown)	https://www.amazon.com/dp/B00PIPCGWC?ref=ppx_yo2ov_dt_b_fed_asin_title	
MHQJRH M.2 2280 SSD heatsink, Double-Sided Heat Sink, with Thermal Silicone pad for PC / PS5 M.2 PCIE NVMe SSD or M.2 SATA SSD	https://www.amazon.com/dp/B07KDDKDNN?ref=ppx_yo2ov_dt_b_fed_asin_title	Attached to the download M.2 drive.
GLOTRENDS M.2 Heatsink for 2280 M.2 SSD, Fit for PC/PS5/PS5 Slim Installation, 22x70x3mm Aluminum Body, Including Thermal Pad	https://www.amazon.com/dp/B076YZMQR5?ref=ppx_yo2ov_dt_b_fed_asin_title	Attached to the dual app/vm M.2 drives.
10Gtek 2-Port M.2 NVMe Adapter M-Key, PCIe X8 Gen3. Requires Motherboard BIOS Support for Bifurcation	https://www.amazon.com/10Gtek-B09NKTYFHX/dp/B09NKTYFHX/ref=sr_1_2?dib=eyJ2IjoiMSJ9.IpKG29j7_cybvmDBbOD0-TLG2co2cp-A5LOKM0JWCL5k2tvq29m6viW6Jh23XWJ0gvwIZIXvWpi3ggM71wuE4ZDNJmHVDLwWUeCIFJfjpF-3siuwnzFQ6BBsR41aYst9yGBIYKIKItzGo_NizrvtXOy2qiAAX8oFFc4Errkm58OyYmyOcEMthTrBeXztgmzlk1zdwycfCQJkv7uxntT9xPkpxgH0cgWTluMW1zMlOSU.nowNg6R5wLMPh_ZRYC3paHhxS8RoowaVKuecD03bicA&dib_tag=se&keywords=10gek%2Bm.2%2Bpcie&qid=1724980752&sr=8-2&th=1	Holds the two 256GB M.2 drives for apps/vms
GLOTRENDS PA09-HS M.2 NVMe to PCIe 4.0 X4 Adapter with M.2 Heatsink for M.2 NVMe SSD	https://www.amazon.com/GLOTRENDS-Adapter-Aluminum-Heatsink-PA09_HS/dp/B07FN3YZ8P/ref=sr_1_1?crid=2AJYL2TWS5JWK&dib=eyJ2IjoiMSJ9.zj7_Ua8lCuXLDp_ooryVc5F5lkvJjv_l7Cj8bPG4TWyZtta9ZHob9ASOLB-xQ6bSxA8fkrSXZqbtv7nTiDliQyaoucbhIweJEfw_XWDnL7lsI4gnw-fgIzcC2zLYhB0wmBfsIOUh4rwPA69ukSI7jCRjnaiNcK1fCQ7xz6HuKc7e-tTobWZvd1Hd-fHiXAdM-aZ7anlPDC5ifnrysYEVOVl45Eovu10uoyJLiBg4Kdbi1XpDPhWsMllJp-VgZ3HrZNP_NZSCA5HhE1SdZUcbM_Cx-EGxfUxS4NWmZ5QJEbU.ISewvE6K7hR8VLSpd6N2tOnQOpAlKFffzCema175qTY&dib_tag=se&keywords=glotrend+m.2+card&qid=1724980976&s=electronics&sprefix=glotrend+m.2+card%2Celectronics%2C84&sr=1-1	Holds the M.2 for download extraction.
SXTAIGOOD MCX311A-XCAT ConnectX-3 EN 10G Ethernet 10GbE SFP+ PCI-E NIC	http://www.amazon.com/gp/product/B0BYDB3TS1	Connects to a SFP in a Ubiquiti 24 port POE switch.
H!Fiber.com 2 Pack SFP+ Cable, 10G SFP+ DAC, 2M(6.6ft), Passive Direct Attach Copper Twinax Cable for Cisco SFP-H10GB-CU2M, Ubiquiti UniFi 	https://www.amazon.com/dp/B09K7FZZPB?ref=ppx_yo2ov_dt_b_fed_asin_title	One for the unRAID server and one for a dedicated storage server.
Thermaltake Toughpower GX2 80+ Gold 600W SLI/Crossfire Ready Continuous Power ATX 12V V2.4/EPS V2.92 Non Modular Power Supply 5 Year Warran	https://www.amazon.com/dp/B087CDR14Z?psc=1&ref=ppx_yo2ov_dt_b_product_details	



# unRAID Storage Server


# Game Rig


# Test Bench

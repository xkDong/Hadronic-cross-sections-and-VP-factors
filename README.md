# Hadronic cross sections and timelike vacuum polarization

[Download the v13 data release](https://github.com/xkDong/Hadronic-cross-sections-and-VP-factors/releases/tag/v13-compact).

| Dataset | Contents |
| --- | --- |
| [Global](https://github.com/xkDong/Hadronic-cross-sections-and-VP-factors/releases/download/v13-compact/global-v13.zip) | Total hadronic Born cross section, hadronic $R$ ratio and timelike vacuum polarization on 17,554 energy points, with pointwise lower and upper errors. |
| [Charm](https://github.com/xkDong/Hadronic-cross-sections-and-VP-factors/releases/download/v13-compact/charm-v13.zip) | Total spectrum and pointwise errors from 3.7 to 5 GeV. |
| [Bottom](https://github.com/xkDong/Hadronic-cross-sections-and-VP-factors/releases/download/v13-compact/bottom-v13.zip) | Total spectrum and pointwise errors from 10.55852 to 11.2062 GeV. |

The output grid is refined around narrow resonances. At the 39,137 reference energies, linear interpolation in energy reproduces the central $R$ and $V$ curves to within 0.1%.

Each ZIP contains `spectrum.csv` and a column guide. The interval for each nominal value X is [X − err_minus, X + err_plus]. Near narrow resonances the bounds enclose the central 68.27% of the propagated distribution; a skewed distribution can place the nominal value outside these bounds.

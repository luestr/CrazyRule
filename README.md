## 🛡 800万广告拦截规则暴力压测

为了避免一次加载海量规则容易让代理工具无限崩溃导致只能重装的问题，我把接近800万条的规则按照每10万条分割成一个文件的形式做成切片；

目前总计个79个文件，方便各位压测；

已经按照各代理工具对应的书写格式编写了配置，可直接在配置文件内粘贴，详见下文；

如果你想挑战800万条的单个规则集，可以查看页面底部内容。

------------


#### Loon - RULE-SET格式

Loon可直接复制下面的内容粘贴到`[Remote Rule]`下，请不要一次全部复制，建议逐次添加，避免代理工具无限崩溃。

```
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_1.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_2.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_3.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_4.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_5.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_6.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_7.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_8.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_9.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_10.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_11.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_12.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_13.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_14.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_15.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_16.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_17.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_18.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_19.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_20.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_21.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_22.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_23.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_24.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_25.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_26.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_27.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_28.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_29.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_30.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_31.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_32.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_33.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_34.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_35.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_36.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_37.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_38.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_39.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_40.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_41.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_42.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_43.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_44.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_45.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_46.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_47.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_48.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_49.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_50.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_51.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_52.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_53.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_54.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_55.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_56.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_57.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_58.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_59.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_60.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_61.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_62.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_63.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_64.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_65.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_66.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_67.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_68.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_69.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_70.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_71.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_72.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_73.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_74.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_75.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_76.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_77.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_78.list, policy = REJECT, tag = 疯狂的规则, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/Loon/ad-loon_79.list, policy = REJECT, tag = 疯狂的规则, enabled = true
```

------------


#### Surge - DOMAIN-SET格式

Sure可直接复制下面的内容粘贴到`[Rule]`下，请不要一次全部复制，建议逐次添加，避免代理工具无限崩溃。

```
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_1.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_2.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_3.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_4.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_5.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_6.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_7.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_8.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_9.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_10.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_11.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_12.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_13.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_14.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_15.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_16.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_17.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_18.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_19.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_20.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_21.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_22.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_23.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_24.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_25.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_26.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_27.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_28.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_29.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_30.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_31.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_32.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_33.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_34.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_35.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_36.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_37.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_38.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_39.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_40.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_41.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_42.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_43.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_44.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_45.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_46.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_47.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_48.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_49.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_50.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_51.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_52.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_53.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_54.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_55.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_56.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_57.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_58.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_59.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_60.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_61.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_62.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_63.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_64.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_65.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_66.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_67.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_68.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_69.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_70.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_71.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_72.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_73.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_74.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_75.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_76.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_77.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_78.list, REJECT
DOMAIN-SET, https://raw.githubusercontent.com/luestr/CrazyRule/main/Surge/ad-surge_79.list, REJECT
```

------------


#### Quantumult X - 专用格式，请勿开解析器

Quantumult X可直接复制下面的内容粘贴到`[filter_remote]`下，请不要一次全部复制，建议逐次添加，避免代理工具无限崩溃。

```
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_1.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_2.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_3.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_4.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_5.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_6.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_7.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_8.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_9.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_10.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_11.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_12.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_13.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_14.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_15.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_16.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_17.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_18.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_19.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_20.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_21.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_22.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_23.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_24.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_25.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_26.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_27.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_28.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_29.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_30.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_31.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_32.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_33.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_34.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_35.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_36.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_37.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_38.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_39.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_40.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_41.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_42.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_43.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_44.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_45.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_46.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_47.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_48.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_49.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_50.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_51.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_52.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_53.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_54.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_55.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_56.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_57.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_58.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_59.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_60.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_61.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_62.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_63.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_64.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_65.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_66.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_67.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_68.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_69.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_70.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_71.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_72.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_73.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_74.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_75.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_76.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_77.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_78.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
https://raw.githubusercontent.com/luestr/CrazyRule/main/QuantumultX/ad-quantumult_79.snippet, tag = 疯狂的规则, force-policy = REJECT, opt-parser = false, enabled = true
```

------------


#### Clash / Stash 专用格式

```
rule-providers:
  疯狂的规则1: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_1.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_1.yaml}
  疯狂的规则2: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_2.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_2.yaml}
  疯狂的规则3: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_3.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_3.yaml}
  疯狂的规则4: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_4.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_4.yaml}
  疯狂的规则5: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_5.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_5.yaml}
  疯狂的规则6: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_6.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_6.yaml}
  疯狂的规则7: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_7.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_7.yaml}
  疯狂的规则8: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_8.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_8.yaml}
  疯狂的规则9: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_9.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_9.yaml}
  疯狂的规则10: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_10.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_10.yaml}
  疯狂的规则11: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_11.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_11.yaml}
  疯狂的规则12: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_12.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_12.yaml}
  疯狂的规则13: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_13.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_13.yaml}
  疯狂的规则14: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_14.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_14.yaml}
  疯狂的规则15: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_15.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_15.yaml}
  疯狂的规则16: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_16.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_16.yaml}
  疯狂的规则17: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_17.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_17.yaml}
  疯狂的规则18: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_18.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_18.yaml}
  疯狂的规则19: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_19.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_19.yaml}
  疯狂的规则20: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_20.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_20.yaml}
  疯狂的规则21: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_21.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_21.yaml}
  疯狂的规则22: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_22.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_22.yaml}
  疯狂的规则23: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_23.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_23.yaml}
  疯狂的规则24: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_24.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_24.yaml}
  疯狂的规则25: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_25.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_25.yaml}
  疯狂的规则26: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_26.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_26.yaml}
  疯狂的规则27: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_27.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_27.yaml}
  疯狂的规则28: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_28.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_28.yaml}
  疯狂的规则29: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_29.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_29.yaml}
  疯狂的规则30: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_30.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_30.yaml}
  疯狂的规则31: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_31.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_31.yaml}
  疯狂的规则32: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_32.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_32.yaml}
  疯狂的规则33: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_33.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_33.yaml}
  疯狂的规则34: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_34.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_34.yaml}
  疯狂的规则35: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_35.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_35.yaml}
  疯狂的规则36: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_36.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_36.yaml}
  疯狂的规则37: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_37.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_37.yaml}
  疯狂的规则38: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_38.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_38.yaml}
  疯狂的规则39: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_39.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_39.yaml}
  疯狂的规则40: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_40.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_40.yaml}
  疯狂的规则41: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_41.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_41.yaml}
  疯狂的规则42: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_42.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_42.yaml}
  疯狂的规则43: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_43.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_43.yaml}
  疯狂的规则44: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_44.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_44.yaml}
  疯狂的规则45: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_45.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_45.yaml}
  疯狂的规则46: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_46.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_46.yaml}
  疯狂的规则47: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_47.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_47.yaml}
  疯狂的规则48: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_48.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_48.yaml}
  疯狂的规则49: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_49.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_49.yaml}
  疯狂的规则50: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_50.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_50.yaml}
  疯狂的规则51: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_51.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_51.yaml}
  疯狂的规则52: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_52.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_52.yaml}
  疯狂的规则53: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_53.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_53.yaml}
  疯狂的规则54: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_54.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_54.yaml}
  疯狂的规则55: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_55.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_55.yaml}
  疯狂的规则56: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_56.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_56.yaml}
  疯狂的规则57: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_57.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_57.yaml}
  疯狂的规则58: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_58.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_58.yaml}
  疯狂的规则59: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_59.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_59.yaml}
  疯狂的规则60: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_60.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_60.yaml}
  疯狂的规则61: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_61.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_61.yaml}
  疯狂的规则62: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_62.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_62.yaml}
  疯狂的规则63: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_63.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_63.yaml}
  疯狂的规则64: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_64.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_64.yaml}
  疯狂的规则65: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_65.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_65.yaml}
  疯狂的规则66: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_66.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_66.yaml}
  疯狂的规则67: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_67.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_67.yaml}
  疯狂的规则68: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_68.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_68.yaml}
  疯狂的规则69: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_69.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_69.yaml}
  疯狂的规则70: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_70.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_70.yaml}
  疯狂的规则71: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_71.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_71.yaml}
  疯狂的规则72: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_72.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_72.yaml}
  疯狂的规则73: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_73.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_73.yaml}
  疯狂的规则74: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_74.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_74.yaml}
  疯狂的规则75: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_75.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_75.yaml}
  疯狂的规则76: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_76.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_76.yaml}
  疯狂的规则77: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_77.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_77.yaml}
  疯狂的规则78: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_78.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_78.yaml}
  疯狂的规则79: {type: http, behavior: classical, interval: 86400, path: ./rule-providers/ad-clash_79.yaml, url: https://raw.githubusercontent.com/luestr/CrazyRule/main/Clash/ad-clash_79.yaml}

rules: 
  - RULE-SET,疯狂的规则1,REJECT
  - RULE-SET,疯狂的规则2,REJECT
  - RULE-SET,疯狂的规则3,REJECT
  - RULE-SET,疯狂的规则4,REJECT
  - RULE-SET,疯狂的规则5,REJECT
  - RULE-SET,疯狂的规则6,REJECT
  - RULE-SET,疯狂的规则7,REJECT
  - RULE-SET,疯狂的规则8,REJECT
  - RULE-SET,疯狂的规则9,REJECT
  - RULE-SET,疯狂的规则10,REJECT
  - RULE-SET,疯狂的规则11,REJECT
  - RULE-SET,疯狂的规则12,REJECT
  - RULE-SET,疯狂的规则13,REJECT
  - RULE-SET,疯狂的规则14,REJECT
  - RULE-SET,疯狂的规则15,REJECT
  - RULE-SET,疯狂的规则16,REJECT
  - RULE-SET,疯狂的规则17,REJECT
  - RULE-SET,疯狂的规则18,REJECT
  - RULE-SET,疯狂的规则19,REJECT
  - RULE-SET,疯狂的规则20,REJECT
  - RULE-SET,疯狂的规则21,REJECT
  - RULE-SET,疯狂的规则22,REJECT
  - RULE-SET,疯狂的规则23,REJECT
  - RULE-SET,疯狂的规则24,REJECT
  - RULE-SET,疯狂的规则25,REJECT
  - RULE-SET,疯狂的规则26,REJECT
  - RULE-SET,疯狂的规则27,REJECT
  - RULE-SET,疯狂的规则28,REJECT
  - RULE-SET,疯狂的规则29,REJECT
  - RULE-SET,疯狂的规则30,REJECT
  - RULE-SET,疯狂的规则31,REJECT
  - RULE-SET,疯狂的规则32,REJECT
  - RULE-SET,疯狂的规则33,REJECT
  - RULE-SET,疯狂的规则34,REJECT
  - RULE-SET,疯狂的规则35,REJECT
  - RULE-SET,疯狂的规则36,REJECT
  - RULE-SET,疯狂的规则37,REJECT
  - RULE-SET,疯狂的规则38,REJECT
  - RULE-SET,疯狂的规则39,REJECT
  - RULE-SET,疯狂的规则40,REJECT
  - RULE-SET,疯狂的规则41,REJECT
  - RULE-SET,疯狂的规则42,REJECT
  - RULE-SET,疯狂的规则43,REJECT
  - RULE-SET,疯狂的规则44,REJECT
  - RULE-SET,疯狂的规则45,REJECT
  - RULE-SET,疯狂的规则46,REJECT
  - RULE-SET,疯狂的规则47,REJECT
  - RULE-SET,疯狂的规则48,REJECT
  - RULE-SET,疯狂的规则49,REJECT
  - RULE-SET,疯狂的规则50,REJECT
  - RULE-SET,疯狂的规则51,REJECT
  - RULE-SET,疯狂的规则52,REJECT
  - RULE-SET,疯狂的规则53,REJECT
  - RULE-SET,疯狂的规则54,REJECT
  - RULE-SET,疯狂的规则55,REJECT
  - RULE-SET,疯狂的规则56,REJECT
  - RULE-SET,疯狂的规则57,REJECT
  - RULE-SET,疯狂的规则58,REJECT
  - RULE-SET,疯狂的规则59,REJECT
  - RULE-SET,疯狂的规则60,REJECT
  - RULE-SET,疯狂的规则61,REJECT
  - RULE-SET,疯狂的规则62,REJECT
  - RULE-SET,疯狂的规则63,REJECT
  - RULE-SET,疯狂的规则64,REJECT
  - RULE-SET,疯狂的规则65,REJECT
  - RULE-SET,疯狂的规则66,REJECT
  - RULE-SET,疯狂的规则67,REJECT
  - RULE-SET,疯狂的规则68,REJECT
  - RULE-SET,疯狂的规则69,REJECT
  - RULE-SET,疯狂的规则70,REJECT
  - RULE-SET,疯狂的规则71,REJECT
  - RULE-SET,疯狂的规则72,REJECT
  - RULE-SET,疯狂的规则73,REJECT
  - RULE-SET,疯狂的规则74,REJECT
  - RULE-SET,疯狂的规则75,REJECT
  - RULE-SET,疯狂的规则76,REJECT
  - RULE-SET,疯狂的规则77,REJECT
  - RULE-SET,疯狂的规则78,REJECT
  - RULE-SET,疯狂的规则79,REJECT
```

------------


## ⚠ 未拆分的规则文件

❗️ 把玩前，建议提前备份配置文件，避免无法挽救；

❗️ 可能有极高的概率让iOS端的代理工具无限崩溃，且只能重新安装方可解决；

❗️ 规则文件在200MB~310MB左右，可能比较容易下载规则失败，需要较好的网络。

#### Loon / Surge / Egern/ LanceX / Shadowrocket - RULE-SET格式

https://github.com/Potterli20/file/releases/download/ad-hosts-pro/ad-surge.yaml

#### Quantumult X - 专用格式

https://github.com/Potterli20/file/releases/download/ad-hosts-pro/ad-quantumult.yaml

#### Clash / Stash

https://github.com/Potterli20/file/releases/download/ad-hosts-pro/ad-clash.yaml
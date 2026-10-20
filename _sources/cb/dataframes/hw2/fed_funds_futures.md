# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures

Daily UTC trading dates with symbol, open, high, low, close and volume. Includes calendar spreads; filter outright monthly ZQ contracts before inferring rates. Prices equal 100 minus the monthly average effective federal funds rate in percentage points.


## DataFrame Glimpse

```
Rows: 11755
Columns: 7
$ date   <datetime[ns]> 2026-10-19 00:00:00
$ symbol          <str> 'ZQN7'
$ open            <f64> 95.45
$ high            <f64> 95.45
$ low             <f64> 95.375
$ close           <f64> 95.38
$ volume          <u64> 1479


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 |                                    |
| Tags                           |                                              |
| Access Types                   |                                       |
| How is data pulled?            | Databento Historical API, GLBX.MDP3, ohlcv-1d, ZQ.FUT parent                                                   |
| Data available up to (min)     | 2026-10-19 00:00:00                                                             |
| Data available up to (max)     | 2026-10-19 00:00:00                                                             |
| Dataframe Path                 | /private/tmp/claude-501/-Users-wyy-Documents-Uchi-MSFM-commodity-fundamentals-research/90fb92e2-abd7-4386-811b-2d1980828806/scratchpad/hw2build/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///private/tmp/claude-501/-Users-wyy-Documents-Uchi-MSFM-commodity-fundamentals-research/90fb92e2-abd7-4386-811b-2d1980828806/scratchpad/hw2build/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-20 00:11:06           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```


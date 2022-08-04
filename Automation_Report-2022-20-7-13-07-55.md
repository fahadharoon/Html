::: {#theme-selector alt="Click to toggle theme. To enable by default, use theme configuration." title="Click to toggle theme. To enable by default, use theme configuration."}
*desktop\_windows*
:::

::: {.nav-wrapper}
[Extent](http://extentreports.relevantcodes.com){.brand-logo .blue
.darken-3}

-   [*dashboard*](#!)
-   [*track\_changes*](#!)

[ExtentReports]{.report-name} []{.report-headline}
:::

::: {.container}
::: {#test-view .view}
::: {#controls .section}
::: {.controls .grey .lighten-4}
::: {.chip .transparent}
[*warning* Status](#){.dropdown-button .tests-toggle}

-   [Pass *check\_circle*](#!)
-   [Fail *cancel*](#!)
-   [Error *error*](#!)
-   [Warning *warning*](#!)
-   [Skip *redo*](#!)
-   
-   [Clear Filters *clear*](#!)
:::

::: {.chip .transparent .hide}
[*close* Clear]{#clear-filters}
:::

::: {#toggle-test-view-charts .chip .transparent}
[*track\_changes* Dashboard]{#enable-dashboard .pink-text}
:::

::: {.chip .transparent alt="Search Tests" title="Search Tests"}
[*search* Search](#){.search-div}

::: {.input-field .left .hide}
:::
:::
:::
:::

::: {#test-view-charts .subview-full}
::: {#charts-row .row .nm-v .nm-h}
::: {.col .s12 .m4 .l4 .np-h}
::: {.card-panel .nm-v}
::: {.left .panel-name}
Features
:::

::: {.chart-box}
:::

::: {.block .text-small}
[0]{.strong} test(s) passed
:::

::: {.block .text-small}
[1]{.strong} test(s) failed, [0]{.strong} others
:::
:::
:::

::: {.col .s12 .m4 .l4 .np-h}
::: {.card-panel .nm-v}
::: {.left .panel-name}
Scenarios
:::

::: {.chart-box}
:::

::: {.block .text-small}
[0]{.strong} step(s) passed
:::

::: {.block .text-small}
[1]{.strong} step(s) failed, [0]{.strong} others
:::
:::
:::

::: {.col .s12 .m4 .l4 .np-h}
::: {.card-panel .nm-v}
::: {.left .panel-name}
Steps
:::

::: {.chart-box}
:::

::: {.block .text-small}
[1]{.strong} step(s) passed
:::

::: {.block .text-small}
[1]{.strong} step(s) failed, [0]{.strong} others
:::
:::
:::
:::
:::

::: {.subview-left .left}
::: {.view-summary}
##### Tests

-   ::: {.test-heading}
    [CASapi2]{.test-name} [7/20/2022 1:07:55 PM]{.test-time}
    [Fail]{.test-status .right .fail}
    :::

    ::: {.test-content .hide}
    ::: {.scenario .node test-id="2" status="fail"}
    [00:03:07.3019851]{.scenario-duration .right .label}
    ::: {.scenario-desc}
    **Scenario** Verify that user can link account to alias
    :::

    -   **Given** the test case title is \"Link Account To Alias\"
    -   **Given** update the data by query \"Begin delete from
        IRIS\_TRANSACTION.TRANSACTION\_LOG t where
        t.SOURCE\_CHANNEL\_KEY = \'500005020253\';commit;End;\"
        ::: {.pre}
        ORA-12154: TNS:could not resolve the connect identifier
        specified
        :::
    :::
    :::
:::
:::

::: {.subview-right .left}
::: {.view-summary}
#####  {#section .test-name}
:::
:::
:::

::: {#exception-view .view .hide}
::: {#controls .section}
::: {.controls .grey .lighten-4}
::: {.chip .transparent alt="Search Tests" title="Search Tests"}
[*search* Search](#){.search-div}

::: {.input-field .left .hide}
:::
:::
:::
:::

::: {.subview-left .left}
::: {.view-summary}
##### Exceptions
:::
:::

::: {.subview-right .left}
::: {.view-summary}
#####  {#section-1 .exception-name}
:::
:::
:::

::: {#dashboard-view .view .hide}
::: {.card-panel .transparent .np-v}
##### Dashboard

::: {.row}
::: {.col .s2}
::: {.card-panel .r}
Features

::: {.panel-lead}
1
:::
:::
:::

::: {.col .s2}
::: {.card-panel .r}
Scenarios

::: {.panel-lead}
1
:::
:::
:::

::: {.col .s2}
::: {.card-panel .r}
Steps

::: {.panel-lead}
2
:::
:::
:::

::: {.col .s2}
::: {.card-panel .r}
Start

::: {.panel-lead}
7/20/2022 1:07:55 PM
:::
:::
:::

::: {.col .s2}
::: {.card-panel .r}
End

::: {.panel-lead}
7/20/2022 1:11:20 PM
:::
:::
:::

::: {.col .s2}
::: {.card-panel .r}
Time Taken

::: {.panel-lead}
00:03:24.9101132
:::
:::
:::
:::
:::
:::
:::

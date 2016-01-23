###make_transition_table

***Description***

Creates transition table.

***Synopsis***

    template <class... Ts>
    auto make_transition_table(Ts...) noexcept;


***Semantics***

    make_transition_table(transitions...);

***Requirements***

| Parameter | Requirement | Description | Returns |
| --------- | ----------- | ----------- | ------- |
| Ts        | transitional| transitions | list of transitions |

***Header***

    #include <boost/msm/msm.hpp>

***Example***
![CPP](https://raw.githubusercontent.com/boost-experimental/msm-lite/master/example/reference/make_transition_table.cpp)

Change the array using <a href="http://www.w3schools.com/js/js_array_methods.asp" target="_blank">standard methods</a> and reassign it to the **dataSource** option using the [option(optionName, optionValue)](/api-reference/10%20UI%20Widgets/Component/3%20Methods/option(optionName_optionValue).md '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Methods/#optionoptionName_optionValue') method.

    <!--JavaScript-->
    var fruits = [
        { fruit: 'Apples', count: 10 },
        { fruit: 'Oranges', count: 12 },
        { fruit: 'Lemons', count: 15 }
    ];

    fruits.push({ fruit: 'Pineapples', count: 3 });
    $("#chartContainer").dxChart("option", "dataSource", fruits);

#####See Also#####
- [Get and Set Options - jQuery](/concepts/58%20jQuery%20Components/20%20Component%20Configuration%20Syntax/05%20Get%20and%20Set%20Options/00%20Get%20and%20Set%20Options.md '/Documentation/Guide/jQuery_Components/Component_Configuration_Syntax/#Get_and_Set_Options')
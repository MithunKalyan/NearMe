# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImageMap</title>
</head>
<style>
    *{margin: 0;}
</style>
<script>
    function coordinate(event)
    {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("Text1").value=x;
        document.getElementById("Text2").value=y;
    }
</script>
<body>
    <IMG src="mkm.png" width="1535" height="650" usemap="#MapNew" onmousemove="coordinate(event)">
        <MAP name="MapNew">
                    <AREA shape="rect" coords="539,345,667,407" href="https://www.goibibo.com/hotels/meta/google/4354390963378411938/3540257811845764463/%7B%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22ibp%22:%22v15%22%7D/?hquery={%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22qd%22:%2220240413-20240414-1-2_0%22,%22ibp%22:%22v15%22}&utm_source=meta&cmp=META|google|cpc_hpa|googlehoteldfinder|Hotel_Price_Ads_3540257811845764463|META&utm_medium=cpc_hpa&utm_campaign=Hotel_Price_Ads_19905350044_3540257811845764463&vendor=gds&p=1636.40&c=INR&bookingSource=commissions&adType=1&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iq5W5ntjSqfMfzNq0F0wSaCOn3dwkJw3Tig3aqE1EUBWPbvzKjAhcaArdQEALw_wcB" title="Country club Lee Crysstal - Boutique Hotel">
                        <AREA shape="rect" coords="742,162,919,218" href="https://www.makemytrip.com/hotels/hotel-listing/?topHtlId=202109211631562045&city=CTMAA&country=IN&checkin=04132024&checkout=04142024&roomStayQualifier=2e0e&totalGuestCount=2&roomCount=1&cmp=googlehoteldfinder_DH_META_Paid_selected_IN_mapresults_202109211631562045&_uCurrency=INR&Campaign=20607960138&locusId=CTMAA&locusType=city&mtkeys=3ea0338e-cf36-453a-bc7c-c382698d6ca7&au=&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5gWDllpXvek6_tZCDcm1sRYgZE-3w3I1jYg2b3tZrbNOFVXFiORQK4aAhM3EALw_wcB" title="Le Grace chennai ECR">
                            <AREA shape="rect" coords="1102,397,1302,447" href="https://www.goibibo.com/hotels/meta/google/4354390963378411938/9148435948091139586/%7B%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22ibp%22:%22%22%7D/?hquery={%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22qd%22:%2220240413-20240414-1-2_0%22,%22ibp%22:%22%22}&utm_source=meta&cmp=META|google|cpc_hpa|googlehoteldfinder|Hotel_Price_Ads_9148435948091139586|META&utm_medium=cpc_hpa&utm_campaign=Hotel_Price_Ads_19905408880_9148435948091139586&vendor=&p=21186.90&c=INR&bookingSource=commissions&adType=1&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iVKB2gnAmkqssixOUUTLRI5VUHnbzeIEoIB9OKpfHmnlCtRsgHHs4aApKbEALw_wcB" title="Mer Vue Villa (Beach house)">
        </MAP>
        <br>
        X-coordinate
            <input type="text" id="Text1">
        Y-coordinate 
            <input type="text" id="Text2">
</body>
</html>
```


## OUTPUT:
![outweb1](https://github.com/MithunKalyan/NearMe/assets/148410106/c430461f-25ce-4577-82f3-f6418392344c)

![outweb2](https://github.com/MithunKalyan/NearMe/assets/148410106/98924a2a-b331-4f4a-9a38-61fb6153e4d8)

![outweb3](https://github.com/MithunKalyan/NearMe/assets/148410106/bb9632c4-b599-4d34-ad2f-ff054021faef)

![outweb4](https://github.com/MithunKalyan/NearMe/assets/148410106/1d40c788-4251-4048-b42f-c12f5dba9b3e)

![outweb5](https://github.com/MithunKalyan/NearMe/assets/148410106/75259ac7-f502-4ff9-977b-847c98f3e2b7)




## RESULT
The program for implementing image maps using HTML is executed successfully.

# TreadFarmland

## Add Event
- TreadFarmland\event\TreadFarmlandEvent extends BlockPlaceEvent
````php
	public function onBlockPlace(BlockPlaceEvent $event){
		if($event instanceof TreadFarmlandEvent){
			echo "Handle TreadFarmlandEvent";
		}
	}
````

## Replace Player class
- TreadFarmland\player\TreadFarmLandPlayer extends Player

## Reference
- PMMP is not break the crops when floor block is not farmland
- Just check 'isTransparent()'
- Therefore, If you want to work properly, should apply the [CropPlus](https://github.com/organization/CropPlus) on PMMP.



```
```

```
```

```
```


# in Korean 한국어

## 이벤트 추가
- TreadFarmland\event\TreadFarmlandEvent extends BlockPlaceEvent
````php
	public function onBlockPlace(BlockPlaceEvent $event){
		if($event instanceof TreadFarmlandEvent){
			echo "Handle TreadFarmlandEvent";
		}
	}
````

## Player클래스를 치환
- TreadFarmland\player\TreadFarmLandPlayer extends Player

## 참조
- PMMP가 바닥이 경작지가 아닐때 작물을 부수지않습니다.
- 단지 'isTransparent()'만 체크합니다.
- 그러므로, 당신이 이것이 제대로 작동하기 원한다면, 반드시 [CropPlus](https://github.com/organization/CropPlus)를 PMMP에 적용해야합니다.
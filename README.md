

# Implant ID Web  
<br/>

>임플란트 ID Front-End Part입니다.

<br/>

<div  align="center"> 
	<h1> ✨ Tech Stack ✨ </h1>
<br/>
	<h3> Frameworks  & Languages & Libraries 🔥</h3>
<br/>
	<div  align="center">
		<!-- 1st Layer -->
		<div align="center">
			<!--HTML -->
				<img align="center" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white"/>
			<!--CSS -->
				<img align="center" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white"/>
			<!--Javascript -->
				<img align="center" src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat&logo=javascript&logoColor=white"/>
		</div>
		<!-- 2nd Layer -->
		<div align="center">
			<!--Vue3 -->
				<img align="center" src="https://img.shields.io/badge/Vue3-4FC08D?style=flat&logo=vuedotjs&logoColor=white"/>
			<!--Typescript -->
				<img align="center" src="https://img.shields.io/badge/Typescript-3178C6?style=flat&logo=typescript&logoColor=white"/>
			<!--SCSS -->
				<img align="center" src="https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white"/>
			<!--Vite -->
				<img align="center" src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white"/>
		</div>  
		<!-- 3rd Layer -->
		<div align="center">
			<!--Vue-router -->
				<img align="center" src="https://img.shields.io/badge/Vue_router-v.4.1.6-4D4D4D?labelColor=E71B34" />
			<!--Pinia -->
				<img align="center" src="https://img.shields.io/badge/Pinia-v.2.0.33-4D4D4D?labelColor=139BB4"/>
			<!--Axios -->
				<img align="center" src="https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white">
			<!--Tui-image-editor -->
				<img align="center" src="https://img.shields.io/badge/Tui_image_editor-v.3.15.3-4D4D4D?labelColor=00B388">
		</div>
	</div>
<br/><br/>
</div>  


<br/>

# Table of Contents
<br/>

* ### [Implant ID Web](#implant-id-Web)
* ### [Table of Contents](#table-of-contents)
* ###  [Features](#features)
* ### [Progress](#progress)
* ### [Caution](#caution)
* ### [Code Instruction](#code-instruction)
	* #### [1.Vue3(Composition API)](#1.vue3(composition-api))
	* #### [2.Pinia Store(setup stores)](#2.pinia-store(setup-stores))
	* #### [3.Vue-router](#3.vue-router)
	* #### [4.Axios](#4.axios)
	* #### [5.Tui-image-editor](5.tui-image-editor)


<br/>  

# Features

<br/> 

* ### 로그인 / 로그아웃
* ### 프로필 수정 및 삭제
* ### 사진 편집
* ### 특정 사진의 임플란트 제작사와 모델 명을 AI를 이용하여 추정
* ### 검색 기록 조회 및 필터 검색
* ### 전문 판정 단의 2차 판정 등록
* ### 사용자 정보 조회 및 검색, 등록, 수정, 삭제
* ### 병원 정보 조회 및 검색, 등록, 수정, 삭제
* ### 제품 정보 조회 및 검색, 등록, 수정, 삭제
* ### 메뉴 정보 조회 및 검색, 등록, 수정, 삭제
* ### 코드 정보 조회 및 검색, 등록, 수정, 삭제

<br/>  

# Progress

<br/>  

> ### 1.로그인 페이지
* 기능 개발 및 디자인 작업 완료
* 특이사항: 없음
<br/><br/> 

> ### 2. 찾기 페이지
* 기능 개발 및 디자인 작업 완료
* 특이사항: Rotation 기능 및 detecting 기능 추가 개발 검토 중
<br/><br/>

> ### 3. 사용 내역 페이지
* 기능 개발 및 디자인 작업 완료
* 특이사항: 
	* 판별 결과 페이지 결과 보고서 출력 부분 publishing에 문제가 있음.(디자이너 님께 요청 필요)
	* 기타 제품을 적을 경우 제작사 명이 포함되어 있는지 제작사는 고르고 적는 것인지 결정 필요
<br/><br/>  

> ### 4. 사용자 관리 페이지
* 기능 개발 및 디자인 작업 완료
* 특이사항: 없음
<br/><br/>  

> ### 5. 병원 관리 페이지
* 기능 개발 및 디자인 작업 완료
* 특이사항: 병원 등록 api에서 관리자 정보 부분 미 개발 상태
<br/><br/>  

> ### 6. 제품 관리 페이지
* 페이지 라우팅 완료
* 기능 미 개발
* 디자인 작업 진행 중
* 특이사항: 없음
<br/><br/>  

> ### 7. 메뉴 관리 페이지
* 페이지 라우팅 완료
* 기능 미 개발
* 디자인 작업 진행 중
* 특이사항: 없음
<br/><br/>  

> ### 8. 코드 관리 페이지
* 페이지 라우팅 완료
* 기능 미 개발
* 디자인 작업 진행 중
* 특이사항: 없음
<br/><br/>  

> ### 9. 프로필 페이지
* 기능 개발 및 디자인 작업 완료
* 특이사항: 없음
<br/><br/>  

> ### 10. 서비스 약관 및 개인정보 보호 정책 페이지
* 페이지 라우팅 완료 및 디자인 작업 진행 중
* 특이사항: 없음
<br/><br/>  


# Caution

<br/>  

> ### 1. 환경 변수 관리  

   * env.[개발 모드] 파일에서 관리되고 있음.  
   * vite-plugin-environment을 이용해서 process.env에서 직접 접근 가능한 변수 명을 지정할 수 있음.  
   
   <br/>  
     
> ### 2. build 관련 명령(package.json 참고)  

   * run: npm run serve:[개발 모드]
   * build: npm run build:[개발 모드]  
   <br/>  
     
> ### 3. Script Setup & Composition API  

 > **Warning**  
 >Vue3의 Script setup과 Composition API를 이용하여 개발  
 >이에 대하여 **<u>모를 경우 필히 사용법에 대해 숙지하는 것이 필요함</u>**  
 
<br/>

> **참고자료:**  
* https://vuejs.org/api/sfc-script-setup.html#script-setup       
* https://vuejs.org/guide/extras/composition-api-faq.html#what-is-composition-api  
* https://vuejs.org/api/composition-api-setup.html
  
<br/>  

# Code Instruction
<br/>  

## 1.Vue3(Composition API)  
<br/>  

## 2.Pinia Store(setup stores)  
<br/>  

> **Note**  
> ### Resources:
> https://pinia.vuejs.org/core-concepts/#setup-stores  
> https://pinia.vuejs.org/core-concepts/#what-syntax-should-i-pick
> ### API Docs: 
> https://pinia.vuejs.org/api/modules/pinia.html#Enumerations

<br/>

### Set & Export

```Typescript
/*   testStore.ts  */
import { defineStore } from "pinia";
import { Ref, reactive, ref } from "vue";

const testStore = defineStore(
	"test",
	()=> {
		const user: Ref<string> = ref(""); // 모든 타입 사용 가능하지만 사용시 .value를 붙여야함.
		const list = reactive({}); 
		// array 또는 object만 사용 가능, array의 경우 반영이 안되는 경우 있었음
		// 웬만하면 object에만 사용하거나 ref 사용하길 권장
		const subFunc = ()=> {
			console.log("sub function");
		}
		const testFunc = ()=>{
			subFunc();
			console.log("test function");
		};							
		return { user, testFunc }; // 외부 파일에서 사용할 변수, 함수들 Export 처리
	},
	{
		persist: {
			storage: localStorage, // 스토리지 선택
			paths: [
				"user" // persist 적용할 변수 또는 함수 명시
	      ],
	   },
	}
};

export default testStore
```
<br/>  

### Import & Use

```Typescript
/*   testPage.vue  */
import { TestStore } from "@/store";
import { toRefs,onMounted } from "vue";

const testStore = TestStore(); // TestStore 인스턴스 생성

const { user, testFunc } = toRefs(testStore); // 구조 분해 할당

onMounted(()=>{
	user.value = "James";
	console.log(user.value);
	testFunc.value();
});

```
<br/>  

## 3.Vue-router

### Routing pages

```Typescript
import { createWebHistory, createRouter} from "vue-router";

const routes = [
	{ // 1.basic routing
		path: "/",
		name: "index",
		component: () => import("@/views/IndexView.vue"), // lazy loading
	},
	{ // 2.routing with params
		path: "/:id",
		name: "login",
		component: () => import("@/views/LoginView.vue"), // lazy loading
	},
	{ // 3.routing subpages
		path: "/main",
		name: "main",
		component: () => import("@/views/MainView.vue"), // lazy loading
		children: [
			{
	        path: "subpage1", //  sub url은 "/" 붙이지 않습니다.
	        name: "subpage1",
	        component: () => import("@/components/Subpage1.vue"),
	      },
	      {
	        path: "subpage2", 
	        name: "subpage2",
	        component: () => import("@/components/Subpage2.vue"),
	      },
		]
	},
]

const router = createRouter({
  history: createWebHistory(),
  routes,
});

export { router };
```
<br/>  

### useRoute & useRouter

```Typescript
import { useRoute, useRouter } from "vue-router";

const route = useRoute();
const router = useRouter();

const moveToIndex = async()=> {
	await router.push("/");
}

const moveToSub1 = async()=> {
	await router.push("/main/subpage1");
}

let params = Ref("");

const getParams = () => {
	params.value = route.params.id;
}

```
<br/>  

## 4.Axios  
<br/>  

> **Note**    
>### Official site: https://axios-http.com/docs/intro  
>### Github: https://github.com/axios/axios  

<br/>  


### Basic usage

```Typescript
const API_URL = process.env.API_URL;
const config = { 
	baseURL: API_URL,
	timeout: 30000, 
	headers: {authorization: "token"} 
}

const instance = axios.create(config);
```

>### Configuration available options: https://axios-http.com/docs/req_config  

<br/>

### Used Cases

```Typescript
import axios from "./axios";
import Config from "./config";

 /* Get */
 getData: (_params?: Object) => {
    const config = new Config().default;
    config.params = { ..._params };
    return axios.get("/suburl", config);
 },

 /* Post */
 postData: (_body: Object, token: string) => {
    const config = new Config().default;
    config.headers.authorization = token;
    return axios.post("/suburl", _body, config);
  },
  
  /* Put */
  putData: (_body: Object, id: string, token: string) => {
    const config = new Config().default;
    config.headers.authorization = token;
    return axios.put(`/suburl/${id}`, _body, config);
  },

	/* delete */
  deleteData: (token: string, id: string) => {
    const config = new Config().default;
    config.headers.authorization = token;
    return axios.delete(`/suburl/${id}`, config);
  },
```
<br/> 

### Interceptors  

```Typescript

/* request interceptor */
axios.interceptors.request.use(
	(config) => { 
		// request를 보내기 전에 공통적으로 설정을 추가하거나 변경
		return config; 
	}, 
	(error) => { 
		// request error가 발생할 경우 처리 로직
		return Promise.reject(error); 
	}
); 

/* response interceptor */
axios.interceptors.response.use(
	(response) => { 
		// 2XX status code
		// 정상적으로 데이터를 받았을 경우 공통 처리 로직 
	return response; 
	}, 
	(error) => { 
		// status code 2XX를 벗어나는 경우
		// 에러 발생시 처리 로직(switch 등을 이용해 status code마다 다르게 처리 가능)
		const response: AxiosResponse = error.response;
		const status = response.status;

		switch(status) {
			case xxx:
				/* status code xxx일 경우 처리 로직 */
				doSomething();
				break;
			default:
				return Promise.reject(error);
		}
		return Promise.reject(error); 
	}
);

```
<br/>  

## 5.Tui-image-editor
<br/>  

> **Note**    
>### Official site: http://nhn.github.io/tui.image-editor/latest/
>### Github: https://github.com/nhn/tui.image-editor/tree/master/apps/image-editor
>### Demo:http://nhn.github.io/tui.image-editor/latest/tutorial-example01-includeUi

<br/>  

### Create instance(minimal option)  

```HTML
<!-- test.html -->
<body>
  ...
  <div id="tui-image-editor"></div>
  ...
</body>
```

```Typescript
/* test.ts */
 const ImageEditor = require('tui-image-editor');
 const instance = new ImageEditor(document.querySelector('#tui-image-editor'), {
 /* 이미지가 그려질 캔버스의 사이즈 지정 */
  cssMaxWidth: 700, 
  cssMaxHeight: 500,
});
```

<br/>

### 

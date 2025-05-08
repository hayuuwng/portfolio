# 배움과 경험, 성장하기
### 창작물 중에서도 <ins>성장과 경험을</ins> 지향하는 게임을 통해 사람들에게 새로운 경험과 즐거움을 나누고 싶습니다.
### 다양한 장르의 게임을 분석하고, 게임 개발을 시도했습니다. 

간단하게 로그로 구현한 턴제 게임의 기획과 로그화면

![Image](https://github.com/user-attachments/assets/620f479b-9a75-4804-b15d-67988543930e)

![Image](https://github.com/user-attachments/assets/461567e5-01ce-4b29-ab6e-f3d2c7213d4a)

![Image](https://github.com/user-attachments/assets/739c466c-8532-417b-b016-5b9c51da3b6f)

# 시도의 폭 넓히기
### 창작의 폭을 넓히기 위해 개발이라는 한 우물은 계속 파되, <br>업계 통용 표준 기술 또한 익히며 게임 개발을 위한 기반을 다져왔습니다.
### 1인 게임 개발자로서의 성장을 위한 노력일 뿐만 아니라, <br>팀 프로젝트에서 다양한 분야와 원활히 협업하기 위한 준비이기도 했습니다.

게임 개발자 인터뷰 정리

![image](https://github.com/user-attachments/assets/f92acfde-aa68-4103-954f-4d53fa6502a1)


게임 산업 분석 노트

![Image](https://github.com/user-attachments/assets/b434b494-d081-42d6-9010-fb012a7931be)

'스토리 모드', '전투 모드'에 대한 시스템 기획

![Image](https://github.com/user-attachments/assets/b203d6df-537c-4521-9ca4-f43396efa6d0)

소설 필체 분석

![Image](https://github.com/user-attachments/assets/a34606cb-7ca7-420b-b620-c67d4ad554a2)

애니메이팅

![Image](https://github.com/user-attachments/assets/a2bed5a9-446c-4a35-89e9-7f5d7a68a059)
![그레이브](https://github.com/user-attachments/assets/76ba8303-54e9-422e-9961-0b189ad21eef)

그림 

![마왕](https://github.com/user-attachments/assets/e3bda805-2d88-4f01-8377-76dd23465630)




# 수정과 피드백하기
### 현재는 유튜브 채널을 운영하고 있지 않지만, <br>작년 여름 동안 유튜브 채널을 운영한 경험이 있습니다.

![Image](https://github.com/user-attachments/assets/5805cb00-bf6c-4a00-9880-863007509142)
![Image](https://github.com/user-attachments/assets/d33f674d-ef93-4740-950a-3fc05a1e9e29)
![Image](https://github.com/user-attachments/assets/29070d9b-cba0-4b91-b93b-ccc6f21c811b)
![Image](https://github.com/user-attachments/assets/3cc206f1-2c34-425a-a857-c9f0f3f07d50)

일부공개 중인 채널의 영상: https://youtube.com/shorts/A6tgLOSEmHE

### 유튜브에서 제공하는 통계 속에서 영상의 어떤 부분에 가장 많은 이탈자가 생겼는지와 같은 **정보파악**을 통해서 자가 피드백을 하였고, <br>덕분에 채널이 성장을 이룰 수 있었습니다.

![Image](https://github.com/user-attachments/assets/e8d9e574-d13c-4e12-9f4e-d81cee71023a)
![Image](https://github.com/user-attachments/assets/09b09004-0ebb-4f2d-9e12-9cc9df4f60bb)
### 일상속에서, 개발 환경에서도 메타인지를 활용하기 위해 노력을 기울이고 있고, 이런 식으로 문제를 해결 할 때 성취감을 느꼈습니다. <br>하지만 어떠한 부분에서 실수를 했고 잘못했는 지를 제시해주는 사람이 없기에 부족한 경험과 지식으로 인하여 그 원인이 잘 보이지 않을 경우에는 많은 시행착오를 겪습니다.
![Image](https://github.com/user-attachments/assets/1b73c23e-e43b-4acf-af65-7905686f65ed)

처음 C언어를 배웠을때
### 저는 그렇기에 다양한 실무 과정을 통한 전문적인 학습 방식과 지식에 대해 배우고자 이 학교에 입학하는 것을 희망합니다. 


# 프로젝트 
## Project 2DMH
저의 프로젝트는 캡콤의 몬스터 헌터 시리즈를 모티브로 제작된 2D 횡스크롤기반 ARPG입니다.
개발 기간은 25년 5월 1일 ~ 입니다.

[GitHub](https://github.com/Murzury/Coding)

## 핵심 플레이
- 커맨드 패턴(콤보구현)
- 보스 패턴

# 개발과정 

커맨드 패턴 방식은 처음 구현해보는 것이었기에 공부가 필요했습니다.

커맨드 패턴이란 명령을 객체로 바꾸는 것으로, 요청을 객체로 캡슐화해서, 서로 다른 요청, 큐잉, 로깅, 실행 취소등을 할 수 있게 해주는 디자인 패턴입니다.
버튼을 눌러서 껐다 킨다고 가정 했을 때,  일반적인 파이썬 코드는 이러한 형태입니다.
```Python
Button.turn_on()
Button.turn_off()
```
하지만 이렇게 직접 호출시에는 요청을 저장하고 취소하는 것이 어렵습니다. 
그런 경우에서 커맨드 패턴으로 전환합니다.
1. Command interface를 만든다.
2. 각각의 명령 객체로 만든다.
3. 명령 객체를 받아서 실행한다.
```css
[Button] --요청--> [Command] --실행--> [Receiver]
```
커맨드 패턴의 장점은 명령을 나중에 실행할 수 있고, 취소하거나 되돌릴 수도 있고, 명령을 리스트로 작성할 수도 있습니다.
입력 히스토리 저장을 통해서 콤보 구현이 가능해지며 추가적인 콤보 기술 추가시에도 커맨드만 만들면 되기에 확장도 쉬워집니다.

이러한 커맨드 패턴을 통해 제가 구현하고자 하는 콤보는 이러합니다.

| 조건   | 입력           | 행동 이름 (예시)        |
| ---- | ------------ | ----------------- |
| 지상   | X            | Attack1           |
|      | C            | Attack2           |
|      | ↓ + X        | DownAttack1       |
|      | ↓ + C        | DownAttack2       |
|      | ↑ + X        | UpAttack1         |
|      | ↑ + C        | UpAttack2         |
| 대시 중 | D + X        | DashAttack1       |
|      | D + C | DashAttack2       |
| 점프 중 | X + X + X    | AirCombo (공중콤보3타) |
|      | C            | AirAttackY        |
|      | ↓ + X        | AirDownAttack1    |
|      | ↓ + C        | AirDownAttack2    |

그리고 제가 PlayerController 스크립트에서 구현한 커맨드 패턴입니다.

## 1. 입력키 -> 문자열 커맨드로 저장
```C#
void RegisterInput(string key)
{
  string dir = GetDirectionKey(); //방향키 조합
  string input = string.IsNullOrEmpty(dir) ? key : dir + " + " + key;
  inputBuffer.Enqueue(input); //ex: "↓ + x"
  lastInputTime = Time. time;

  if (inputBuffer.Count > 3)
    inputBuffer.Dequeue();
}
```
키입력은 명령어 문자열로 변환되어 `Queue`에 저장됩니다. 
이는 하드 코딩된 키값이 아닌 문자열로 다루기 위한 전처리 입니다.

## 2. 커맨드와 실행 함수 매핑

```C#
private Dictionary<string, Action> commandMap = new Dictioncary<string, Action>();

void Start()
{
        commandMap["X"] = Attack1;
        commandMap["C"] = Attack2;
        commandMap["↓+X"] = DownAttack1;
        commandMap["↓+C"] = DownAttack2;
        commandMap["↑+X"] = UpAttack1;
        commandMap["↑+C"] = UpAttack2;
        commandMap["D+X"] = DashAttack1;
        commandMap["D+C"] = DashAttack2;
        commandMap["Jump+X+X+X"] = AirComboAttack;
        commandMap["Jump+C"] = AirAttackY;
        commandMap["Jump+↓+C"] = AirDownAttack1;
        commandMap["Jump+↓+C"] = AirDownAttack2;
}
```
Dictionary<string, Action>은 커맨드 문자열과 해당 커맨드가 수행할 매서드를 연결합니다.
이 구조는 입력과 실행을 분리합니다.

## 3. 입력 버퍼 확인 및 명령 실행

```C#
void CheckCommand()
{
  if (Time.time - lastInputTime > inputBufferTime)
    inputBuffer.Clear();

  string[] combo = inputBuffer.ToArray();
  if(combo.Length == 0) return;

  if (IsJumping() && combo.Length == 3 && combo.All(i => i == "X"))
  {
    commandMap["Jump+X+X+X]?.Invoke(); //공중콤보
    inputBuffer.Clear();
  }

  srting last = combo.Last();
  string commandKey = "";

  if (IsJumping()) commandKey = "Jump+" + last;
  else if (isDashing) commandKey = "D+" + last;
  else commandKey = last;

  if (commandMap.ContainsKey(commandKey))
  {
      commandMap[CommandKey]?.Invoke(); //등록행동실행
      inputBuffer.Clear();
  }
}
```

- `CheckCommand()`는 입력 버퍼를 확인하여, 문자열 커맨드 키를 통해 등록된 메서드를 실행합니다.

- `Invoke()`를 통해 실제 공격 함수(`Attack1()`, `DashAttack2()`, 등)가 호출됩니다.

- 이 구조는 유연하게 커맨드를 추가/수정할 수 있게 해줍니다.

## 주요 요소

  | 요소                               | 커맨드 패턴 역할       |
| -------------------------------- | --------------- |
| `inputBuffer`, `RegisterInput()` | 커맨드 입력 추적       |
| `commandMap`                     | 커맨드 → 행동 매핑 테이블 |
| `CheckCommand()`                 | 명령 판단 및 실행      |
| `Attack1()`, `DownAttack1()` 등   | 커맨드가 실행하는 실제 행동 |

이외에도 `GroundCheck`, `AttackPoint`, `MoveSpeed`, 등 플레이어 조작을 위해 필요한 요소들을 `PlayerController.sc`에 추가하고, 플레이어가 될 오브젝트에 스크립트를 포함한 `Rigidbody 2D`, `Box COllider 2D`같은 컴포넌트를 추가하여 마무리했습니다.


![2025-05-04 15-05-21(1)](https://github.com/user-attachments/assets/8ecd19be-a23f-4f46-b9b7-50d664005985)

캐릭터 움직임은 잘 작동하지만 콘솔창에 오류가 뜨는 것을 볼 수 있습니다.

![image](https://github.com/user-attachments/assets/60364667-7771-4145-8b93-06de5c44f48c)

### 오류내용
```MissingComponentException: "There is no 'Animator' attached to the game object"```
이 오류가 발생하는 상황은 스크립트에서 `GetComponent<Animator>();`를 호출했는데 해당 GameObject에 Animator 컴포넌트가 없는 경우, Animator 기능을 호출할 때 Animator 컴포넌트가 참조되지 않은 경우입니다.
***즉, ~~애니메이션이 존재하지 않는 경우~~ Animator 컴포넌트가 Gameobject에 존재하지 않기에 animator는 null이 되고 매서드를 이에 매서드를 호출할때 이러한 오류가 발생하는 것입니다.*** 
그렇기 때문에 애니메이션을 넣어준다면 해결될 것입니다.

## 전체 스크립트
```c#
using System.Collections.Generic;
using UnityEngine;
using System.Linq;
using System;
  
public class PlayerController : MonoBehaviour
{
    [Header("이동 관련")]
    public float moveSpeed = 5f;
    public float jumpForce = 12f;
    private float horizontalInput;
  
    [Header("대쉬 관련")]
    public float dashSpeed = 15f;
    public float dashDuration = 0.2f;
    public float dashCooldown = 1f;
    private bool isDashing = false;
    private float lastDashTime;
  
    [Header("공격 관련")]
    public Transform attackPoint;         // 타격 기준 위치
    public float attackRange = 1f;        // 타격 범위
    public LayerMask enemyLayer;          // 타격 대상 (적)
  
    [Header("입력 커맨드")]
    private Queue<string> inputBuffer = new Queue<string>();  // 입력 저장 큐
    private float inputBufferTime = 0.5f;   // 입력 유효 시간
    private float lastInputTime;
  
    [Header("기타")]
    public Transform groundCheck;         // 바닥 체크용 위치
    public LayerMask groundLayer;
  
    private Rigidbody2D rb;
    private Animator anim;
    private bool isGrounded;
  
    // 입력 문자열에 따른 공격 동작을 저장하는 사전
    private Dictionary<string, Action> commandMap = new Dictionary<string, Action>();
  
    void Start()
    {
        rb = GetComponent<Rigidbody2D>();
        anim = GetComponent<Animator>();
  
        // 커맨드 키에 대응되는 함수 등록
        commandMap["X"] = Attack1;
        commandMap["C"] = Attack2;
        commandMap["DownArrow"] = DownAction;
        commandMap["↓+X"] = DownAttack1;
        commandMap["↓+C"] = DownAttack2;
        commandMap["↑+X"] = UpAttack1;
        commandMap["↑+C"] = UpAttack2;
        commandMap["D+X"] = DashAttack1;
        commandMap["D+C"] = DashAttack2;
        commandMap["Jump+X+X+X"] = AirComboAttack;
        commandMap["Jump+C"] = AirAttackY;
        commandMap["Jump+↓+X"] = AirDownAttack1;
        commandMap["Jump+↓+C"] = AirDownAttack2;
    }
  
    void Update()
    {
        // 대시 중이 아닐 때만 입력과 이동 처리
        if (!isDashing)
        {
            GetInput();
            Move();
            Jump();
        }
  
        // 대시 시작 조건
        if (Input.GetKeyDown(KeyCode.D) && Time.time >= lastDashTime + dashCooldown && !isDashing)
        {
            StartCoroutine(Dash());
        }
  
        // 버튼 입력 기록
        if (Input.GetKeyDown(KeyCode.X)) RegisterInput("X");
        if (Input.GetKeyDown(KeyCode.C)) RegisterInput("C");
        if (Input.GetKeyDown(KeyCode.Y)) RegisterInput("D");
  
        if (Input.GetKeyDown(KeyCode.DownArrow))
    {
        anim.SetBool("isCrouching", true);
        RegisterInput("Down");  
    }
    else if (Input.GetKeyUp(KeyCode.DownArrow))
    {
        anim.SetBool("isCrouching", false);
    }
  
        // 현재 입력 커맨드 확인 및 실행
        CheckCommand();
  
        // 애니메이션 상태 업데이트
        UpdateAnimation();
    }
  
    void GetInput()
    {
        horizontalInput = Input.GetAxisRaw("Horizontal");
    }
  
    void Move()
    {
        // 좌우 이동
        rb.linearVelocity = new Vector2(horizontalInput * moveSpeed, rb.linearVelocity.y);
  
        // 이동 방향에 따라 캐릭터 방향 전환
        if (horizontalInput != 0)
            transform.localScale = new Vector3(Mathf.Sign(horizontalInput), 1f, 1f);
    }
  
    void Jump()
    {
        // 점프 입력 처리
        isGrounded = Physics2D.OverlapCircle(groundCheck.position, 0.1f, groundLayer);
        if (Input.GetKeyDown(KeyCode.Z) && isGrounded)
        {
            rb.linearVelocity = new Vector2(rb.linearVelocity.x, jumpForce);
        }
    }
  
    IEnumerator Dash()
    {
        // 대시 처리
        isDashing = true;
        lastDashTime = Time.time;
  
        float direction = transform.localScale.x;
        float originalGravity = rb.gravityScale;
  
        rb.gravityScale = 0;
        rb.linearVelocity = new Vector2(direction * dashSpeed, 0f);
  
        yield return new WaitForSeconds(dashDuration);
  
        rb.gravityScale = originalGravity;
        isDashing = false;
    }
  
    void RegisterInput(string key)
    {
        // 방향키와 키 입력을 결합하여 기록 (예: ↓+X)
        string dir = GetDirectionKey();
        string input = string.IsNullOrEmpty(dir) ? key : dir + "+" + key;
  
        inputBuffer.Enqueue(input);
        lastInputTime = Time.time;
  
        // 입력 버퍼는 최대 3개까지만 유지
        if (inputBuffer.Count > 3)
            inputBuffer.Dequeue();
    }
  
    string GetDirectionKey()
    {
        // 누르고 있는 방향키 반환
        if (Input.GetKey(KeyCode.DownArrow)) return "↓";
        if (Input.GetKey(KeyCode.UpArrow)) return "↑";
        return "";
    }
  
    bool IsJumping()
    {
        // 공중 상태 판별
        return !isGrounded && Mathf.Abs(rb.linearVelocity.y) > 0.1f;
    }
  
    void CheckCommand()
    {
        // 입력 시간이 지나면 입력 초기화
        if (Time.time - lastInputTime > inputBufferTime)
            inputBuffer.Clear();
  
        string[] combo = inputBuffer.ToArray();
        if (combo.Length == 0) return;
  
        // 공중 콤보 처리: X+X+X
        if (IsJumping() && combo.Length == 3 && combo.All(i => i == "X"))
        {
            commandMap["Jump+X+X+X"]?.Invoke();
            inputBuffer.Clear();
            return;
        }
  
        string last = combo.Last();
  
        // 현재 상태에 따라 커맨드 키 결정
        string commandKey = "";
        if (IsJumping()) commandKey = "Jump+" + last;
        else if (isDashing) commandKey = "D+" + last;
        else commandKey = last;
  
        // 해당 커맨드가 등록되어 있으면 실행
        if (commandMap.ContainsKey(commandKey))
        {
            commandMap[commandKey]?.Invoke();
            inputBuffer.Clear();
        }
    }
  
    // === 기타 동작 함수들 ===
  
    void DownAction()
    {
        Debug.Log("Down action executed");
    }
  
    // === 공격 관련 함수들 ===
  
    void Attack1()
    {
        anim.SetTrigger("Attack1");
        DoHitDetection();
    }
  
    void Attack2()
    {
        anim.SetTrigger("Attack2");
        DoHitDetection();
    }
  
    void DownAttack1()
    {
        anim.SetTrigger("DownAttack1");
        DoHitDetection();
    }
  
    void DownAttack2()
    {
        anim.SetTrigger("DownAttack2");
        DoHitDetection();
    }
  
    void UpAttack1()
    {
        anim.SetTrigger("UpAttack1");
        DoHitDetection();
    }
  
    void UpAttack2()
    {
        anim.SetTrigger("UpAttack2");
        DoHitDetection();
    }
  
    void DashAttack1()
    {
        anim.SetTrigger("DashAttack1");
        DoHitDetection();
    }
  
    void DashAttack2()
    {
        anim.SetTrigger("DashAttack2");
        DoHitDetection();
    }
  
    void AirComboAttack()
    {
        anim.SetTrigger("AirCombo");
        DoHitDetection();
    }
  
    void AirAttackY()
    {
        anim.SetTrigger("AirC");
        DoHitDetection();
    }
  
    void AirDownAttack1()
    {
        anim.SetTrigger("AirDownX");
        DoHitDetection();
    }
  
    void AirDownAttack2()
    {
        anim.SetTrigger("AirDownC");
        DoHitDetection();
    }
  
    void DoHitDetection()
    {
        // 공격 범위 내 적 탐지
        Collider2D[] hits = Physics2D.OverlapCircleAll(attackPoint.position, attackRange, enemyLayer);
        foreach (Collider2D enemy in hits)
        {
            Debug.Log("타격 성공: " + enemy.name);
            // 적 체력 처리 등의 로직
            // enemy.GetComponent<Enemy>().TakeDamage();
        }
    }
  
    void UpdateAnimation()
    {
        // 이동, 점프, 낙하 애니메이션 상태값 갱신
        anim.SetFloat("Speed", Mathf.Abs(rb.linearVelocity.x));
        anim.SetBool("isGrounded", isGrounded);
        anim.SetFloat("VerticalVelocity", rb.linearVelocity.y);
    }
  
    void OnDrawGizmosSelected()
    {
        // 공격 범위 시각화
        if (attackPoint == null) return;
        Gizmos.color = Color.red;
        Gizmos.DrawWireSphere(attackPoint.position, attackRange);
    }
}
```


대쉬

![2025-05-09 00-03-07(1)](https://github.com/user-attachments/assets/d070bc5f-c692-49ef-9599-9d3c44e3c6a6)








import java.util.Scanner;
import java.util.Random;
import java.util.ArrayList;

public class CommandGame {

    static int level = 1;
    static int exp = 0;
    static int expToNextLevel = 30;
    static int money = 0;

    static int playerMaxHp = 100;
    static int playerHp = 100;
    static int playerMaxMp = 30;
    static int playerMp = 30;
    static int playerAttack = 15;
    static int playerDefense = 5;
    static int playerSpeed = 10;

    static int slimeHp = 80;
    static int slimeMaxHp = 80;
    static int slimeAttack = 8;
    static int slimeDefense = 5;
    static int slimeSpeed = 5;

    static int slimeMoney = 100;
    static int slimeExp = 30;

    static int playerAction = 0;

    static boolean escaped = false;

    static boolean enhanced = false;
    static int enhanceTurns = 0;

    static boolean defending = false;

    static int herbCount = 3;

    static boolean charged = false;

    static boolean weakened = false;
    static int weakenedTurns = 0;

    static boolean burned = false;
    static int burnTurns = 0;
    static int burnDamage = 0;

    static Random random = new Random();

    public static void main(String[] args) throws InterruptedException {

        Scanner scanner = new Scanner(System.in);
        System.out.println();
        System.out.println("==============================");
        System.out.println("         COMMAND GAME         ");
        System.out.println("==============================");
        System.out.println();
        System.out.println("1.ゲームスタート");
        System.out.println("2.ゲーム終了");
        System.out.println();
        System.out.println("コマンドを入力");

        int titleCommand = scanner.nextInt();

        if (titleCommand == 1) {
            System.out.println();
            System.out.println("勇者は旅をしている...");
            Thread.sleep(1400);
            System.out.println("スライムが現れた！");
            Thread.sleep(1400);

        } else if (titleCommand == 2) {
            System.out.println("ゲームを終了します。");
            return;
        }

        // whileの処理
        while (slimeHp > 0 && playerHp > 0 && !escaped) {

            boolean commandSelected = false;
            while (!commandSelected) {

                System.out.println();
                System.out.println("-------------------");
                System.out.println("勇者　　　HP:" + playerHp + "/" + playerMaxHp);
                System.out.println("　　　　　MP:" + playerMp + "/" + playerMaxMp);
                System.out.println();
                System.out.println("スライム　HP:" + slimeHp + "/" + slimeMaxHp);
                System.out.println("-------------------");

                //コマンドの表示

                System.out.println();
                System.out.println("1.たたかう");
                System.out.println("2.にげる");
                System.out.println("3.まもる");
                System.out.println("4.アイテム");
                System.out.println("5.ステータスを表示");
                System.out.println();
                System.out.println("コマンドを入力");
                System.out.println();

                // 勇者の処理
                int command = scanner.nextInt();
                if (command == 1) {

                    System.out.println("行動を選択してください");
                    System.out.println("1.こうげき");
                    System.out.println("2.まほう");
                    System.out.println("3.とくぎ");
                    System.out.println("4.戻る");
                    System.out.println();
                    System.out.println("コマンドを入力");

                    int battleCommand = scanner.nextInt();

                    if (battleCommand == 1) {
                        playerAction = 1;

                        commandSelected = true;

                    } else if (battleCommand == 2) {

                        System.out.println("魔法を選択してください");
                        System.out.println("1.ファイヤー　MP10");
                        System.out.println("2.身体強化　　MP10");
                        System.out.println("3.戻る");
                        System.out.println();
                        System.out.println("コマンドを入力");

                        int magicCommand = scanner.nextInt();

                        if (magicCommand == 1) {
                            playerAction = 2;

                            if (playerMp >= 10) {
                                commandSelected = true;

                            } else {
                                System.out.println();
                                System.out.println("MPが足りないッ!");
                                Thread.sleep(1400);
                            }

                        } else if (magicCommand == 2) {
                            playerAction = 3;

                            if (playerMp >= 10 && !enhanced) {
                                commandSelected = true;

                            } else if (enhanced) {
                                System.out.println();
                                System.out.println("すでに身体強化がかかっているッ！");
                                Thread.sleep(1400);
                            } else {
                                System.out.println();
                                System.out.println("MPが足りないッ！");
                                Thread.sleep(1400);
                            }

                        } else if (magicCommand == 3) {
                            continue;
                        }

                    } else if (battleCommand == 3) {
                        playerAction = 4;
                        commandSelected = true;

                    } else if (battleCommand == 4) {
                        continue;
                    }

                } else if (command == 2) {
                    playerAction = 5;
                    commandSelected = true;

                } else if (command == 3) {
                    playerAction = 6;
                    commandSelected = true;

                } else if (command == 4) {
                    System.out.println("アイテムを選択してください");

                    if (herbCount > 0) {
                        System.out.println("1.薬草 ✕ " + herbCount);
                        System.out.println("2.戻る");
                        System.out.println();
                        System.out.println("コマンドを選択");

                    } else {
                        System.out.println("1.戻る");
                        System.out.println();
                        System.out.println("コマンドを選択");
                    }

                    int itemCommand = scanner.nextInt();

                    if (herbCount > 0 && itemCommand == 1) {

                        if (playerHp == playerMaxHp) {
                            System.out.println();
                            System.out.println("勇者のHPは満タンだ！");
                            Thread.sleep(1400);
                            continue;

                        } else {
                            playerAction = 7;
                            commandSelected = true;
                        }

                    } else if (herbCount > 0 && itemCommand == 2) {
                        continue;

                    } else if (herbCount == 0 && itemCommand == 1) {
                        continue;
                    }

                } else if (command == 5) {

                    System.out.println();
                    System.out.println("------------");
                    System.out.println("  ステータス");
                    System.out.println("------------");
                    System.out.println("レベル:" + level);
                    System.out.println("経験値:" + exp + "/" + expToNextLevel);
                    System.out.println("所持金:" + money + "G");
                    System.out.println("HP:" + playerHp + "/" + playerMaxHp);
                    System.out.println("MP:" + playerMp + "/" + playerMaxMp);
                    System.out.println("攻撃力:" + playerAttack);
                    System.out.println("防御力:" + playerDefense);
                    System.out.println("素早さ:" + playerSpeed);
                    System.out.println("------------");
                    System.out.println();
                    System.out.println("1.戻る");
                    System.out.println("コマンドを選択");

                    int statusCommand = scanner.nextInt();

                    if (statusCommand == 1) {
                        continue;
                    }
                }
            }
            boolean playerFirst;

            if (playerAction == 5 || playerAction == 6 || playerAction == 7 ) {
                playerFirst = true;

            } else if (playerSpeed > slimeSpeed) {
                playerFirst = true;

            } else if (playerSpeed < slimeSpeed) {
                playerFirst = false;

            } else {
                playerFirst = random.nextBoolean();
            }

            if (playerFirst) {
                executePlayerAction();
                executeSlimeAction();

            } else {
                executeSlimeAction();

                if (playerHp > 0) {
                    executePlayerAction();
                }
            }

            if (burned && burnTurns > 0) {
                slimeHp = Math.max(0, slimeHp - burnDamage);
                burnTurns--;

                System.out.println();
                System.out.println("スライムはやけどで" + burnDamage + "ダメージを受けた！");
                Thread.sleep(1400);

                System.out.println("スライム HP:" + slimeHp);

                if (burnTurns <= 0) {
                    burned = false;
                    System.out.println();
                    System.out.println("スライムのやけどが治った！");
                    Thread.sleep(1400);
                }
            }

            //身体強化のターン処理
            if (enhanced) {
                enhanceTurns--;

                if (enhanceTurns <= 0) {
                    enhanced = false;
                    System.out.println();
                    System.out.println("身体強化の効果が切れた！");
                    Thread.sleep(1400);
                }
            }
            if (weakened) {
                weakenedTurns--;

                if (weakenedTurns <= 0) {
                    weakened = false;
                    System.out.println();
                    System.out.println("勇者の攻撃力ダウンの効果が切れた！");
                    Thread.sleep(1400);
                }
            }
            
            playerMp = Math.min(playerMaxMp,playerMp + 2);
                
        }
        if (escaped) {
            System.out.println();
            System.out.println("戦闘を終了した！");

        } else if (slimeHp <= 0 && playerHp > 0) {
            System.out.println();
            System.out.println("スライムを倒した！");
            Thread.sleep(1400);
            System.out.println("勝利！");
            Thread.sleep(1400);

            money += slimeMoney;
            System.out.println("お金を" + slimeMoney + "G獲得した!");

            exp += slimeExp;
            System.out.println("経験値を" + slimeExp + "獲得した！");
            Thread.sleep(1400);

            while (exp >= expToNextLevel) {
                exp -= expToNextLevel;
                level++;

                playerMaxHp += 10;
                playerMaxMp += 3;

                playerHp = playerMaxHp;
                playerMp = playerMaxMp;

                playerAttack += 2;
                playerDefense += 1;
                playerSpeed += 1;

                expToNextLevel = (int) Math.round(expToNextLevel * 1.2);

                System.out.println();
                System.out.println("レベルアップ!");
                Thread.sleep(1400);
                System.out.println("勇者はLv." + level + "になった!");
                Thread.sleep(1400);
            }

        } else if (playerHp <= 0) {
            System.out.println();
            System.out.println("勇者は力尽きた...");
            Thread.sleep(1400);
            System.out.println("ゲームオーバー！");
        }
    }
    public static void executePlayerAction() throws InterruptedException {
        if (playerAction == 1) {
            int damage = (playerAttack - slimeDefense) + random.nextInt(-2, 3);
            damage = Math.max(0, damage);

            System.out.println();
            System.out.println("勇者はスライムを攻撃した！");
            Thread.sleep(1400);

            if (random.nextInt(4) == 0) {
                damage = (playerAttack * 2 - slimeDefense) + random.nextInt(-2, 3);
                System.out.println("会心の一撃！");
                Thread.sleep(1400);
            }
            if (enhanced) {
                damage = (int) Math.round(damage * 1.5);
            }
            if (weakened) {
                damage = (int) Math.round(damage * 0.7);
            }

            slimeHp = Math.max(0, slimeHp - damage);

            System.out.println("スライムに" + damage + "ダメージ！");
            Thread.sleep(1400);
            System.out.println("スライム HP:" + slimeHp);
            Thread.sleep(1400);

        } else if (playerAction == 2) {

            playerMp = playerMp - 10;

            System.out.println();
            System.out.println("勇者はファイヤーを唱えた！");
            Thread.sleep(1400);

            int fireDamage = random.nextInt(20, 26);
            int damage = (fireDamage - slimeDefense);

            damage = Math.max(0, damage);
            slimeHp = Math.max(0, slimeHp - damage);

            System.out.println("スライムに" + damage + "ダメージ！");
            Thread.sleep(1400);

            if (random.nextInt(10) < 3) {
                burned = true;
                burnTurns = random.nextInt(2, 5);
                burnDamage = random.nextInt(2, 6);

                System.out.println("スライムはやけどを負った！");
                Thread.sleep(1400);
            }

            System.out.println("スライム HP:" + slimeHp);
            Thread.sleep(1400);

        } else if (playerAction == 3) {
            playerMp = playerMp - 10;
            enhanced = true;
            enhanceTurns = 4;
            System.out.println();
            System.out.println("勇者は身体強化を使った！");
            Thread.sleep(1400);
            System.out.println("3ターンの間、攻撃力が1.5倍になる！");
            Thread.sleep(1400);

        } else if (playerAction == 4) {
            System.out.println();
            System.out.println("勇者は腹踊りをした！");
            Thread.sleep(1400);

            if (random.nextInt(5) == 0) {
                slimeHp = Math.max(0, slimeHp - 9999);

                System.out.println("スライムは腹を抱えて笑った！");
                Thread.sleep(1400);
                System.out.println("スライムに9999ダメージ！");
                Thread.sleep(1400);
            } else {
                System.out.println("しかし、何も起こらなかった！");
                Thread.sleep(1400);
            }

        } else if (playerAction == 5) {
            System.out.println("勇者は逃げ出した！");
            Thread.sleep(1400);

            if (random.nextInt(2) == 0) {
                escaped = true;

                System.out.println("勇者は逃げ切った！");
                Thread.sleep(1400);

            } else {
                System.out.println("しかし、逃げられなかった！");
                Thread.sleep(1400);

            }

        } else if (playerAction == 6) {
            System.out.println("勇者は身を固めた！");
            Thread.sleep(1400);

            defending = true;

        } else if (playerAction == 7) {
            int beforeHp = playerHp;

            playerHp = Math.min(playerMaxHp, playerHp + 20);
            herbCount--;

            int healedHp = playerHp - beforeHp;

            System.out.println();
            System.out.println("勇者は薬草を使った！");
            Thread.sleep(1400);

            System.out.println("勇者のHPが" + healedHp + "回復した！");
            Thread.sleep(1400);

            System.out.println("勇者 HP:" + playerHp);
            Thread.sleep(1400);
        }
    }
    public static void executeSlimeAction() throws InterruptedException {
        // スライムの処理
        if (!escaped && slimeHp > 0) {

            System.out.println();

            ArrayList<Integer> actions = new ArrayList<>();
            ArrayList<Integer> weights = new ArrayList<>();

            actions.add(1); //攻撃
            weights.add(30);

            if (!charged) {
                actions.add(2); //蓄える
                weights.add(20);
            }

            if (slimeHp <= 60) {
                actions.add(3); //雑草を食べる
                weights.add(15);
            }

            if (!weakened) {
                actions.add(4); //かわいこぶる
                weights.add(15);
            }

            actions.add(5); //ぷにぷに
            weights.add(20);

            int totalWeight = 0;

            for (int weight : weights) {
                totalWeight += weight;
            }

            int roll = random.nextInt(totalWeight);

            int slimeAction = 0;

            for (int i = 0; i < actions.size(); i++) {
                roll -= weights.get(i);

                if (roll < 0) {
                    slimeAction = actions.get(i);
                    break;
                }
            }

            if (slimeAction == 1) {
                int slimeDamage = (slimeAttack - playerDefense) + random.nextInt(-2, 3);
                slimeDamage = Math.max(0, slimeDamage);

                if (defending) {
                    slimeDamage = (int) Math.round(slimeDamage * 0.5);
                }
                if (charged) {
                    slimeDamage = slimeDamage * 2;
                    charged = false;
                }

                playerHp = Math.max(0, playerHp - slimeDamage);

                System.out.println("スライムの攻撃！");
                Thread.sleep(1400);
                System.out.println("勇者に" + slimeDamage + "ダメージ！");
                Thread.sleep(1400);
                System.out.println("勇者 Hp:" + playerHp);
                Thread.sleep(1400);

            } else if (slimeAction == 2) {
                System.out.println("スライムは力を蓄えている..!");
                Thread.sleep(1400);

                charged = true;

            } else if (slimeAction == 3) {
                int beforeHp = slimeHp;
                slimeHp = Math.min(slimeMaxHp, slimeHp + 10);
                int healedHp = slimeHp - beforeHp;

                System.out.println("スライムは雑草を食べた！");
                Thread.sleep(1400);
                System.out.println("スライムのHPが" + healedHp + "回復した！");
                Thread.sleep(1400);
                System.out.println("スライム HP:" + slimeHp);
                Thread.sleep(1400);

            } else if (slimeAction == 4) {
                System.out.println("スライムはかわいこぶっている..!");
                Thread.sleep(1400);
                weakened = true;
                weakenedTurns = 3;
                System.out.println("勇者の攻撃力が下がった！");
                Thread.sleep(1400);

            } else if (slimeAction == 5) {
                System.out.println("スライムはぷにぷにしている...");
                Thread.sleep(1400);

                if (random.nextInt(5) == 0) {
                    System.out.println("ぷに.....ぷにぷにぷにぷにぷに!");
                    Thread.sleep(1400);

                    playerHp = 0;
                    System.out.println("勇者は9999ダメージを受けた！");
                    Thread.sleep(1400);

                    System.out.println("勇者 HP:" + playerHp);
                    Thread.sleep(1400);
                }
            }
            defending = false;
        }
    }
}

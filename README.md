# 基于C++语言设计的量化高频交易系统

im_not_real

## 1.设计思路与目的

在现代金融体系中，出现了众多基于计算机的高效率，高性能设计出的交易系统。
计算机高性能计算的特点让交易系统能够更准确地捕捉到金融市场的变化，从而更有可能实现盈利。
而在计算机高级语言中，C++又因为其高性能低延迟的特点，常常被用于搭建交易系统。
笔者将基于C++语言设计一个简单的，初步的量化交易系统。

## 2.项目总体框架

笔者将设计一个trading类，用于模仿市场的走向并包含交易策略。
其中函数成员包含了构造函数，用于初始化市场的基本参数如交易金额或市场价格。
用calculate，trade函数，用于自动获取市场交易信息，在获取到市场的价格的基础上计算获利概率，
通过移动平均线的交易策略决定是否交易等等。将会在代码中编写注释介绍，在此不一一介绍。

## 3.项目优势

项目基于移动平均线的交易策略，该交易策略是基于经济学与概率学的，帮助进行系统的量化交易。
项目完全实现了自动化，只需用户进行简单的初始化后便可自动的进行交易。
项目特别设计了交易历史记录系统，可以让用户了解过往交易盈亏从而调整参数。

## 4.问题与解决办法

本项目的设计目的是实现一个高性能的交易系统，但本项目并没有完全的实现高性能的特点，
也就是说并没有发挥出C++的语言特性。但碍于笔者的算法知识和金融知识有限，
无法设计出更加高效的算法，只能改变一种更加科学和高效的交易策略。

## 5.运行环境

在本地环境下：（windows11系统+Visual Studio 2022 ISO C++14 标准）代码能够正常通过编译并运行，
建议在本地运行时至少选择C++14以上的标准，以防产生意料之外的错误。

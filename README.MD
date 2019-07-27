# AssistantD
An innovative Brazilian virtual assistant whose main proposal is to discover diseases and treatment modes
  

﻿/*
 * Created by SharpDevelop.
 * User: usuario
 * Date: 29/05/2019
 * Time: 21:16
 * 
 * To change this template use Tools | Options | Coding | Edit Standard Headers.
 */
using System;

namespace ic
{
	class Program
	{
		public static void Main(string[] args)
		{
		start:
			Console.WriteLine("olá eu sou o seu médico pessoal, irei te ajudar a encontrar a doença e como trata-la");
			Console.ReadKey(true);
			Console.Clear();
			
			Console.WriteLine("você é o paciente");
			
			Console.WriteLine("você sabe com que doença está? (s ou n)");
			string pergunta=(Console.ReadLine());
			if ((pergunta == "sim"));{ goto sintomas;}
			
			if ((pergunta=="nao")){goto start;}
			
		
		
		
		
		
		
		sintomas:
			Console.WriteLine("você sabe que doença você tem mas não sabe seus sintomas ou como trata-la? (s ou n)");
			string duvida=(Console.ReadLine());
			if ((duvida=="sim")){goto doenças;}
			if ((duvida=="nao")){goto start;}
			goto start;
			Console.ReadKey(true);
		
		
		
		
		
		
		
		
		doenças:
			Console.WriteLine("então escolha uma dessas opções");
			Console.WriteLine("\t1 - gripe");
            Console.WriteLine("\t2 - resfriado");
            Console.WriteLine("\t3 - catapora");
            Console.WriteLine("\t4 - emorroida");
            Console.WriteLine("\t5 - fissura anal");
            Console.Write("ecolha a sua opção");

            switch (Console.ReadLine()){
            		case "1":
            	Console.WriteLine("A gripe é uma doença muito comum A gripe ataca os pulmões, o nariz e a garganta.");
                     Console.WriteLine("Crianças pequenas, idosos, gestantes e pessoas com doenças crônicas ou imunidade baixa correm alto risco.");
                       Console.WriteLine("");
                          Console.WriteLine("OS SINTOMAS DA GRIPE incluem febre, calafrios, dores musculares, tosse, congestão, coriza, dores de cabeça e fadiga.");
                              Console.WriteLine("");                          
                                 Console.WriteLine("A gripe é tratada principalmente com repouso e ingestão de líquidos para permitir que o corpo combata a infecção por conta própria.");
                                        Console.WriteLine("Analgésicos anti-inflamatórios vendidos sem prescrição médica podem ajudar com os sintomas.");
                                         Console.WriteLine("Uma vacina anual pode ajudar a prevenir a gripe e limitar suas complicações.");
                                          Console.WriteLine("");
                                           Console.WriteLine("evite beijar ou tocar algo ou alguem com gripe");
                                            Console.WriteLine("");
                                             
                                             
                    break;
                case "2":
                    Console.WriteLine("O resfriado é uma doença comum que pode ser causada por muitos virus diferentes.");
                     Console.WriteLine("");
                       Console.WriteLine(" A a condição costuma ser inofensiva e os sintomas geralmente desaparecem depois de uma ou duas semanas.");
                        Console.WriteLine("");
                         Console.WriteLine("os sintomas são=> dores locais: dores o musculo, nos ouvidos ou seios paranasais.");
                          Console.WriteLine("");
                           Console.WriteLine("Tosse: seca.");
                            Console.WriteLine("");
                            Console.WriteLine("No nariz: congestão, nariz escorrendo, perda de olfato, vermelhidão, espirros ou gotejamento pós-nasal");
                             Console.WriteLine("");
                              Console.WriteLine("Também é comum: dor de cabeça, inchaço dos gânglios, olhos marejados, pressão no peito ou privação de sono, além de uma febre de até 39,5°");
                               Console.WriteLine("");
                                Console.WriteLine("para conter os sintomas do resfriado basta tomar: vitaminas, analgésicos e descongestionantes nasais");
                                 Console.WriteLine("");
                                  Console.WriteLine("");
                                   Console.WriteLine("");
                                    Console.WriteLine("");
                                     Console.WriteLine("");
                                      Console.WriteLine("");
                                       Console.WriteLine("");
                                        Console.WriteLine("");
                                         Console.WriteLine("");
                    break;
                case "3":
                    Console.WriteLine("Your result: {num1} * {num2} = ");
                    break;
                case "4":
                    Console.WriteLine("Your result: {num1} / {num2} = ");
                    break;
            }
            Console.ReadKey(true);
		}
	}
